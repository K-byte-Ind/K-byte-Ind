Design of Autonomous Aircraft – Ground-to-Air Drone Detection

Camera-Based UAV Detection using YOLOv8 and Custom Dataset

📌 Project Overview

This project implements a camera-based pipeline to detect unauthorized drones as part of the Design of Autonomous Aircraft course. The system leverages YOLOv8 trained on a custom dataset of ~2700 annotated images to achieve high-accuracy drone detection.

The broader course also included a LiDAR-based detection pipeline (ROS + MATLAB), but this repository specifically covers the camera-based YOLOv8 pipeline implemented in Python.

🗂 Project Structure
.
├── DAA_Final_Project_v1.ipynb   # Jupyter Notebook with full pipeline
└── README.md                    # Project documentation

⚙️ Tools & Technologies

Programming: Python

Frameworks & Libraries: YOLOv8, Roboflow, OpenCV, NumPy, Pandas

Platform: Google Colab

Dataset: ~2700 images annotated using Roboflow

🚀 Workflow

Dataset Preparation

Annotated ~2700 drone images using Roboflow.

Exported in COCO format → converted to YOLO format.

Model Training

Used YOLOv8l architecture.

Trained for 50 epochs on Google Colab with GPU acceleration.

Evaluation

Achieved Precision: 96.5%, Recall: 96.9%, mAP@50: 96.2%.

Output bounding boxes with confidence scores.

📈 Results

Robust detection of drones in test images.

High precision and recall demonstrate the model’s suitability for real-world UAV surveillance tasks.

Provides a foundation for integration with multi-sensor fusion (LiDAR + Camera).

📊 Sample Metrics
Metric	Value
Precision	96.5%
Recall	96.9%
mAP@50	96.2%
mAP@50-95	50.8%
👨‍💻 Author

Kotireddy Syamala

M.Sc. Autonomous Vehicle Engineering, University of Naples Federico II

LinkedIn: kotireddy-syamala

Email: kotireddyr3@gmail.com

✨ This project highlights expertise in dataset preparation, deep learning-based object detection, and UAV-focused AI applications.
