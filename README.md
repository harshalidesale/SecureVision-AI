YOLOv8 Object Detection
Project Overview

This project uses YOLOv8 for real-time object detection.
The model identifies objects in images and videos and draws bounding boxes with class labels and confidence scores.

YOLOv8 is fast, accurate, and suitable for surveillance and security-related applications.

Technologies Used

Python

YOLOv8

OpenCV

PyTorch

Features

Real-time object detection

Image and video processing

Pretrained YOLOv8 models

Easy integration with Python applications

Installation

Install required packages using pip:

pip install ultralytics

Usage
Run Detection Using Python
from ultralytics import YOLO

model = YOLO("yolo11n.pt")
results = model("image.jpg")
results.show()

Use Cases

Surveillance and security monitoring

Threat detection

Smart city applications

Industrial monitoring

Future Enhancements

Custom model training

Integration with web dashboards

Cloud deployment

Conclusion

This project demonstrates how YOLOv8 can be used for fast and reliable object detection and can be extended for real-world applications.
