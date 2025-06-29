# raspberry-plate-recognition

License plate detection using computer vision on Raspberry Pi (resource-optimized).

This is the most minimalistic version of the project [https://github.com/Charlyhno-eng/LicensePlateRecognitionCV](https://github.com/Charlyhno-eng/LicensePlateRecognitionCV). The goal is to keep it as lightweight as possible to run efficiently on a Raspberry Pi.

For my part, I did not test via a raspberry but I tested via my phone's camera. To do this, I used the DroidCam application (there are similar applications on IOS). You just have to enter the IP address that is written when launching your application. This requires your phone to be on the same network as your PC or to be connected to your PC.

Currently suitable for Romanian license plates. If you want other formats, please create them in the plate_format folder.

## Installation

- python3 -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
- sudo apt install tesseract-ocr

## Usage

- python plate_detector_live.py

---

## Next evolution

The next evolution will be to move the model to ONNX and do all the processing in Rust
