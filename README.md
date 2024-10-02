# Helmet Detection Using YOLOv7 and YOLOv8
## Overview

This project implements object detection using YOLOv7 and YOLOv8 deep learning models to detect helmets worn by workers in industrial environments, such as warehouses and construction sites. The goal is to enhance workplace safety by automating the detection of workers wearing safety helmets.

The project involves the following key tasks:

   - **Data Collection**: Manually collected image datasets of workers in industrial settings.
   - **Data Annotation**: Images were annotated using Roboflow to identify helmets on workers.
   - **Model Training**: YOLOv7 and YOLOv8 models were trained on the annotated dataset.
   - **Model Evaluation**: Performance was evaluated using metrics such as precision, recall, and mean average precision (mAP).
   - **Deployment**: The models can be used to detect helmets in real-time for safety monitoring.

## Models

This project explores the performance of two advanced object detection models:

   - **YOLOv7**: Known for high recall, making it suitable for detecting all positive instances (i.e., helmets).
   - **YOLOv8**: Known for high precision, making it ideal for minimizing false positives in helmet detection.

## Key Features

- **Precision and Recall**: YOLOv7 achieved a precision of **0.97** and recall of **1.0**, while YOLOv8 achieved a precision of **0.98** and recall of **0.92**.
- **Mean Average Precision (mAP)**: YOLOv7 achieved **0.99** mAP@IOU=0.5, while YOLOv8 achieved **0.98** mAP@IOU=0.5.
- **Automation**: The system automates helmet detection, enhancing safety compliance and reducing the need for manual checks.


## Tools and Libraries

- **YOLOv7** and **YOLOv8**: For object detection.
- **TensorFlow**: Used for model implementation and training.
- **Roboflow**: For data annotation and preprocessing.
- **Python**: The main programming language used.
