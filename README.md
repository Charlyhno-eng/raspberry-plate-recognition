# raspberry-plate-recognition

License plate detection using computer vision on Raspberry Pi (resource-optimized).

This is the most minimalistic version of the project [https://github.com/Charlyhno-eng/LicensePlateRecognitionCV](https://github.com/Charlyhno-eng/LicensePlateRecognitionCV). The goal is to keep it as lightweight as possible to run efficiently on a Raspberry Pi.

Currently suitable for Romanian license plates. If you want other formats, please create them in the plate_format folder.

## Installation

- python3 -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
- sudo apt install tesseract-ocr

## Usage

- python plate_detector_live.py
