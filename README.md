# raspberry-plate-recognition

License plate detection using computer vision on Raspberry Pi (resource-optimized).

This is the most minimalistic version of the project [https://github.com/Charlyhno-eng/license-plate-recognition-CV](https://github.com/Charlyhno-eng/license-plate-recognition-CV). The goal is to keep it as lightweight as possible to run efficiently on a Raspberry Pi.

Currently suitable for Romanian license plates. If you want other formats, please create them in the plate_format folder.

## Installation

- sudo apt install tesseract-ocr

- python3 -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt

## Usage

- python3 -m venv venv
- source venv/bin/activate
- python plate_detector_live.py

---

## Next evolution

The next evolution will be to move the model to ONNX and do all the processing in Rust
