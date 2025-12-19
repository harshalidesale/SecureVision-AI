🚀 YOLOv8 Object Detection
📌 Project Overview

This project implements YOLOv8 for real-time object detection.
It detects objects in images and videos and displays bounding boxes with class labels and confidence scores.

YOLOv8 is fast, accurate, and suitable for security and surveillance applications.

🛠️ Technologies Used

Python

YOLOv8

PyTorch

OpenCV

✨ Features

✅ Real-time object detection

✅ Image and video input support

✅ Pretrained YOLOv8 models

✅ Easy Python integration

📦 Installation

Install the required library using pip:

pip install ultralytics

▶️ Usage
🔹 Run Detection Using Python
from ultralytics import YOLO

model = YOLO("yolo11n.pt")
results = model("image.jpg")
results.show()

🎯 Use Cases

🔐 Surveillance systems

🚨 Threat detection

🏙️ Smart city monitoring

🏭 Industrial safety

🔮 Future Enhancements

Custom dataset training

Web dashboard integration

Cloud deployment (AWS)

✅ Conclusion

This project shows how YOLOv8 can be used for fast and reliable object detection and can be extended for real-world AI-based security systems.
