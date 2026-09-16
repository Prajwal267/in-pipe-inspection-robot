# In-Pipe Inspection Robot Using Machine Learning for Corrosion and Crack Detection

## Project Overview

This project presents a smart in-pipe inspection robot designed to detect corrosion and cracks in pipelines using machine learning and computer vision.

The system integrates a Raspberry Pi 5, Quantron USB camera with IR LEDs, relay-based motor control, and a YOLOv5 deep learning model. A Flask web interface is used to display inspection results.

## Objectives

- Develop a robotic system for pipeline visual inspection.
- Detect corrosion and cracks using machine learning.
- Integrate camera-based image processing with robotic hardware.
- Provide a web-based interface for viewing detection results.

## Hardware Components

- Raspberry Pi 5
- Quantron USB Camera with IR LEDs
- DC Geared Motors
- Relay Module
- Metallic Chassis
- Wooden Platform

## Software and Technologies

- Python
- OpenCV
- YOLOv5
- PyTorch
- NumPy
- Flask
- Raspberry Pi OS
- Google Colab
- Roboflow

## Machine Learning Model

The project uses a YOLOv5 model trained to identify two defect classes:

1. Corrosion
2. Crack

The dataset was prepared using Roboflow and the model was trained using Google Colab.

## System Workflow

1. Camera captures images.
2. Raspberry Pi 5 processes the images.
3. YOLOv5 performs defect detection.
4. Detected defects are displayed through the Flask web interface.
5. Inspection results are logged for review.

## Project Status

Prototype developed for machine learning-based visual defect detection.

## Author

Prajwal H U

M.Tech – Robotics and Artificial Intelligence

Ramaiah Institute of Technology
