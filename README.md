# Drowsiness-Detection
This Drowsiness Detection System is a deep learning-based project designed to monitor a driver's alertness in real-time using computer vision. The system continuously tracks the driver’s eye state through a webcam, and if signs of drowsiness are detected, it triggers an alarm to help prevent accidents.

# How It Works:
1. Camera Activation – The system opens the webcam and monitors the driver’s face every second.
2. Real-time Detection – The model classifies the driver’s state as "Awake" or "Drowsy".
3. Warning Alert – If the driver appears drowsy, an alarm is played immediately to regain attention.

# Model Training Process:
a) Imported necessary libraries, including YOLOv5, OpenCV, Torch, and more.
b) Defined two classes: Drowsy & Awake for classification.
c) Captured and labeled images of both classes to build a dataset.
d) Trained a custom YOLOv5 model on the labeled dataset to detect drowsiness accurately.
e) Implemented real-time monitoring, using threading for efficiency.

# Tech Stack & Libraries Used:
-> YOLOv5 – Deep learning-based object detection
-> Torch – Model training and classification
-> OpenCV (cv2) – Image processing and webcam access
-> Playsound & Pygame – Audio control for warning sounds
-> Matplotlib & NumPy – Data visualization and numerical processing
-> Time & Threading – For efficient execution and real-time performance

This project was an exciting deep dive into computer vision, deep learning, and real-time monitoring for road safety.
