# Crowd-Detection-Model
This project implements a machine learning model designed for detecting and analyzing crowds in various scenarios.
Overview
The Crowd Detection Model is a machine learning-powered solution for identifying and analyzing crowds in video footage. Leveraging the YOLOv8 object detection framework and clustering techniques like DBSCAN, this model detects individuals, evaluates proximity, and highlights persistent crowds. It is designed for applications like public safety, event management, and urban planning.

Features
Object Detection: Uses YOLOv8 to detect people in frames with high accuracy.
Crowd Analysis: Employs DBSCAN clustering to group detected individuals into crowds.
Persistence Tracking: Tracks and logs persistent crowds over consecutive frames.
Automated Logging: Outputs results to CSV files and logs detection activities for further analysis.
Visualizations: Annotates frames with bounding boxes, connections, and crowd labels.
Installation Requirements
Python 3.8 or later
Libraries: cv2, numpy, ultralytics, sklearn, datetime, logging, csv, os
Pre-trained YOLO model (yolov8n.pt)

