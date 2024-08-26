# YOLOV9-Object-Detection
This repository contains the implementation of an object detection project using YOLOv9, the latest evolution in the YOLO (You Only Look Once) family of models. The project demonstrates the ability to detect and classify multiple objects in real-time with high accuracy and efficiency.

Dataset
This project uses the KITTI dataset, which includes 7,481 images.

Image Folder: [Download Images](https://s3.eu-central-1.amazonaws.com/avg-kitti/data_object_image_2.zip)
Label Folder: https://s3.eu-central-1.amazonaws.com/avg-kitti/data_object_label_2.zip
YOLOv9 Repository: https://github.com/WongKinYiu/yolov9?tab=readme-ov-file
Google drive link: https://drive.google.com/drive/folders/1U4AzbCMfdRIYiaJBq9Pw08cZgUxyC5M8?usp=sharing
Setup and Environment
The training environment was set up using Anaconda. Follow these steps to replicate the environment:

Create an Anaconda Environment: A new environment was created in Anaconda, specifically for this project.
Convert Labels to YOLO Format: The downloaded image labels were in COCO format, so they were converted to YOLO format using the file_2_YOLO.ipynb notebook.
Dataset Splitting: The split_dataset.py script was used to split the 7,481 images into 80% training, 10% validation, and 10% test sets. The vp_detection.yaml file contains links to the split folders and now references the split images.
Model Training
Clone YOLOv9 Repository: The YOLOv9 repository was cloned into the newly created Anaconda environment.
Training Environment: The environment was configured for GPU acceleration using an Intel Core i9 processor and Nvidia RTX-4070 GPU.
Training Parameters: The model was trained using the YOLOV9-c.pt weights with the following parameters:
Batch Size: 8
Epochs: 100
Patience: 50
Results
The full training results, including performance metrics and visualizations, can be accessed through the Google Drive link provided.
