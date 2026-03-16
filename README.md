# Object-Detection-Using-Web-Cam
This project performs real-time object detection using YOLOv4 and OpenCV through a webcam. The program captures live video, processes each frame using the YOLOv4 deep learning model, and detects objects with bounding boxes and labels.

## Features

Real-time object detection using YOLOv4

Uses OpenCV DNN module

Detects objects based on COCO dataset classes

Displays bounding boxes, labels, and confidence scores

Live webcam detection with frame visualization using Matplotlib

## Requirements

Python

OpenCV (cv2)

NumPy

Matplotlib

Install dependencies:

```
pip install opencv-python numpy matplotlib
```
## Required Files

Make sure the following files are in the project folder:

yolov4.weights

yolov4.cfg

coco.names

## How It Works

Loads the YOLOv4 model using configuration and weight files.

Reads COCO class labels.

Captures video from the webcam.

Converts each frame into a blob for the neural network.

Runs the frame through the YOLO network.

Applies Non-Maximum Suppression (NMS) to remove overlapping detections.

Draws bounding boxes and labels on detected objects.

Displays the processed frame in real time.

## Output:

The program opens the webcam and displays real-time detected objects with bounding boxes and confidence scores.
