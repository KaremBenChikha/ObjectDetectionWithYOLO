# Object Detection with YOLO

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green)

OpenCV algorithm to detect objects using the YOLO (You Only Look Once) deep learning model.

## Overview

YOLO is a state-of-the-art, real-time object detection system. This project uses OpenCV's DNN module to run YOLOv3 inference on images.

## Setup

```bash
# 1. Install dependencies
pip3 install -r requirements.txt

# 2. Download YOLOv3 weights
# Download yolov3.weights and save it in the yolo/ folder
# https://pjreddie.com/media/files/yolov3.weights

# 3. Add images
mkdir images
# Place your test images inside the images/ folder
```

## Usage

```bash
python3 ObjectDetect.py --image images/your-image.png
```

Press `q` to quit the window.

## Dependencies

- Python 3
- OpenCV
- NumPy
