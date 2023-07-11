# Cable-Damage
Cable Damage Detection with YOLOv8

This repository contains a YOLOv8-based object detection model trained on a custom dataset to identify signs of cable damage. This work could play an instrumental role in improving disaster preparedness and maintaining infrastructure integrity, particularly in regions prone to natural disasters.

# Project Objective

The primary objective of this project is to provide a means to rapidly assess and locate cable damage, whether it be on bridges, power lines, or other similar structures. By facilitating timely detection of infrastructure damage, this model can contribute to the overall safety and efficiency of infrastructure maintenance and disaster response.

# Model Training

The model was trained using a custom dataset specifically compiled for this project. The dataset consists of various images of cables, both in good condition and various stages of damage. YOLOv8 was chosen for this project because of its speed and efficiency in real-time object detection tasks.

# Implementation

Though still in the development phase, the ultimate goal is to build upon this idea and possibly integrate this model into a larger system capable of processing images from various sources (drones, CCTV cameras, etc.) to enable real-time damage detection and reporting.

# How to Use

# Prerequisites: Python 3.x, PyTorch 1.x, and requirements from requirements.txt installed.

Clone this repository: git clone https://github.com/Josee1031/Cable-Damage.git
Install necessary packages from requirements.txt: pip install -r requirements.txt
Run the model on an image: python detect.py --image_path /path/to/your/image.jpg
Future Work

The project could have future developments including:

Improving the model's performance with more data and further tuning
Expanding the scope of the model to detect different types of infrastructure damage
Integrating the model into a real-time monitoring system
