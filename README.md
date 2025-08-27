# Object Detection with YOLOv9

This repository contains an implementation of an object detection project using YOLOv9, the latest evolution of the YOLO (You Only Look Once) family of models. The project showcases YOLOv9’s ability to detect and classify multiple objects in real-time with high accuracy and efficiency.

**📂 Dataset**

The project uses the KITTI dataset, which consists of 7,481 images.

Images: Download here

Labels: KITTI Label Folder

YOLOv9 Repository: YOLOv9 GitHub

Additional Files & Results: Google Drive

**⚙️ Setup & Environment**

The training environment was created using Anaconda.

Steps to replicate:

Create Anaconda Environment

A dedicated environment was created for this project.

Convert Labels to YOLO Format

Original labels were in COCO format.

Converted to YOLO format using file_2_YOLO.ipynb.

Split Dataset

Dataset split into 80% training, 10% validation, 10% testing.

Script: split_dataset.py.

Config: vp_detection.yaml updated to reference split folders.

**🚀 Model Training**

Clone YOLOv9 Repository

Cloned into the Anaconda environment.

**Training Environment**

Hardware: Intel Core i9 + Nvidia RTX 4070 (GPU acceleration enabled).

Training Parameters

Pretrained Weights: YOLOV9-c.pt

Batch Size: 8

Epochs: 100

Patience: 50

**📊 Results**

Training metrics and visualizations are available in the Google Drive folder
.

Results demonstrate YOLOv9’s capability in delivering efficient, real-time object detection with high accuracy on the KITTI dataset.
