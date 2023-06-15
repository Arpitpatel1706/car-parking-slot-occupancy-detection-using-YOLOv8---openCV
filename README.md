# Car Parking Slot Occupancy Detection using YOLOv8, Roboflow & OpenCV
This repository contains a Python project that uses YOLOv8, Roboflow and OpenCV to detect car parking slot occupancy in real-time. The project is divided into three main parts:
## 1. Data Preparation using Roboflow
The first part of the project focuses on preparing the data for training the YOLOv8 model. This involves the following steps:

->Collecting images of parking lots that capture various parking scenarios.

->Annotating the collected images to label the occupied and empty parking slots.

->Utilizing Roboflow as a platform for dataset management, annotation, and augmentation.

->Applying data augmentation techniques to enhance the diversity and robustness of the dataset.

->Exporting the prepared dataset in a format compatible with YOLOv8 training, such as YOLO darknet format or COCO format.

## 2. YOLOv8 Model Training
The second part of the project focuses on training the YOLOv8 model using the prepared dataset. This part includes the following steps:

->Setting up the training environment by installing the required dependencies, including Python, PyTorch, and other necessary libraries.

->Splitting the dataset into training and validation sets to evaluate the model's performance.

->Configuring the YOLOv8 model by specifying the network architecture, hyperparameters, and other settings.

->Initializing the YOLOv8 model architecture and loading pre-trained weights, if available.

->Training the YOLOv8 model using the training dataset and optimizing its parameters to minimize detection errors.

->Monitoring the training progress and evaluating the model's performance using metrics such as loss, precision, recall, and mean average precision (mAP).

->Fine-tuning the model if necessary by adjusting hyperparameters or training for more epochs.

->Saving the trained YOLOv8 model weights for future use during inference.

## 3. Inference
The third part of the project involves using the trained YOLOv8 model to detect car parking slot occupancy in real-time. This part includes the following steps:

->Capturing the parking area image and saving it to disk using the `capture_parking_area.ipynb` notebook.

->Selecting the parking slot coordinates from the captured image using the `select slot coordinates.ipynb` notebook.

->Running the `final_slot_detection.ipynb` notebook to detect empty slots in real-time videos and displaying the total number of empty slots in the parking area.

->Utilizing the YOLOv8 model and OpenCV for real-time object detection and post-processing to identify occupied and empty parking slots.

This project provides a valuable learning opportunity for understanding YOLOv8, OpenCV, and real-time object detection. It offers features such as real-time detection of car parking slot occupancy, ease of use, and well-documented code.

We hope you find this project useful and enjoy exploring its capabilities!
