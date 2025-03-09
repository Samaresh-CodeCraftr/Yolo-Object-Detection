# Yolo-Object-Detection

This project performs real-time object detection using the YOLOv8 model and a webcam. It uses OpenCV to capture video and draw bounding boxes around detected objects.

## Requirements

Make sure you have the following installed:

- Python 3.8+
- OpenCV
- Ultralytics YOLOv8

## Installation

1. Install the dependencies:

```
pip install opencv-python ultralytics
```

## Usage

Run the object detection script:

```
python yolo_detection.py
```

Press 'q' to quit the webcam window.

## How It Works

- Loads the YOLOv8 model (`yolov8n.pt` — lightweight version)
- Captures video from the webcam
- Detects objects in real time and draws bounding boxes with labels and confidence scores
- Displays the output in a pop-up window

## Example Output

Objects like people, cars, and other common items will be detected and labeled live on the video feed.

