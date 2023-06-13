# car parking slot occupancy detection using YOLOv8 & openCV
This repository contains a Python project that uses YOLOv8 and OpenCV to detect car parking slot occupancy in real time. The project is divided into two main parts:  

Data preparation: The first part of the project is to prepare the data for training the YOLOv8 model. This includes collecting images of parking lots, labeling the images with the ground truth information (i.e., which parking spots are occupied and which are empty), and converting the images into a format that can be used by YOLOv8. 

Training and evaluation: The second part of the project is to train and evaluate the YOLOv8 model. This includes training the model on the prepared data, evaluating the model's performance on a held-out test set, and tuning the model's hyperparameters to improve its performance. 

Once the YOLOv8 model is trained, it can be used to detect car parking slot occupancy in real time. This can be done by running the below files:
1.capture_parking_area.ipynb : Used for capturing parking area image and save to disk.
2.select slot coordinates.ipynb: Script, which takes the parking slot coordinates from user.
3.final_slot_detection.ipynb: Script,which uses for detect empty slots for given real-time video and also shows the total numbers of empty slots in parking area.

This project is a great way to learn how to use YOLOv8 and OpenCV to detect objects in real time. It can also be used to build a real-world application that can help people find parking spots more easily.  

Here are some of the features of this project:  
-> Real-time detection of car parking slot occupancy 
-> Easy to use 
->Well-documented

I hope you find this project useful!
