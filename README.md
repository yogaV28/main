Optimized YOLOv8 Architecture for Insect Detection at Agricultural Farms using Intelligent Edge Vision Systems (IEVSs)
Overview
This project aims to develop and deploy an Intelligent Edge Vision System (IEVS) for real-time insect detection and classification in agricultural farms. Leveraging the YOLOv8 model optimized with TensorRT on the Jetson Nano platform, this system provides an efficient and scalable solution for precision agriculture.

Table of Contents
Introduction
Features
System Requirements
Installation
Usage
Datasets
Model Training
Optimization
Inference
Results
Contributors
License
Introduction
Farmers face significant challenges due to insect infestations which can lead to substantial crop losses and economic burdens. This project introduces a real-time insect detection system using optimized YOLOv8 on edge devices to provide early detection and minimize crop damage, thereby promoting sustainable agricultural practices.

Features
Real-time insect detection and classification
Optimized YOLOv8 model for edge devices using TensorRT
High inference speed with low memory requirements
Precision, recall, and F1-scores exceeding 95%
Scalable and deployable on Jetson Nano devices
System Requirements
NVIDIA Jetson Nano
TensorRT 7.0 or higher
Python 3.6 or higher
OpenCV
PyTorch
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/IEVS-insect-detection.git
cd IEVS-insect-detection
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Set up Jetson Nano environment:
Follow the instructions provided by NVIDIA to set up the Jetson Nano and install TensorRT.

Usage
Data Preparation: Collect images of insects and non-insects. Organize them into training and validation sets.
Model Training: Train the YOLOv8 model using the prepared dataset.
Model Optimization: Optimize the trained model using TensorRT for deployment on the Jetson Nano.
Deployment: Deploy the optimized model on the Jetson Nano and start the real-time insect detection.
Datasets
The dataset should include a diverse set of insect images captured in various agricultural settings. Data augmentation techniques are recommended to enhance the model's performance on real-time data.

Model Training
Prepare the dataset and configure the training parameters.
Train the YOLOv8 model using the provided training scripts.
Save the trained model for further optimization.
Optimization
Use TensorRT to optimize the trained YOLOv8 model.
Quantize the model to reduce memory usage and improve inference speed.
Inference
Load the optimized model on the Jetson Nano.
Integrate the camera feed for real-time insect detection.
Run the inference script to start detecting insects.
Results
The optimized YOLOv8 model achieved an inference speed of 45 fps on the Jetson Nano.
High accuracy with precision, recall, and F1-scores exceeding 95%.
Contributors
Balaji Ganesh Rajagopal - SRM Institute of Science and Technology
Jagadeesh Kannan R - SRM Institute of Science and Technology
Omar Khattab - Kuwait College of Science and Technology
M. Omar Al-Kadri - University of Doha for Science and Technology
Somaiyeh MahmoudZadeh - University of Doha for Science and Technology
Yoga Vignesh V - SRM Institute of Science and Technology
Saravana Balaji B - De Montfort University Kazakhstan
License
This project is licensed under the MIT License - see the LICENSE file for details.
