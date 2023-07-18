# Person Detector

# Introduction
The Person Detector is an AI-powered project that utilizes the DetectNet algorithm to detect and locate people in images or video streams. It leverages deep learning techniques and computer vision to accurately identify human figures. This project aims to assist in various applications, including surveillance systems, crowd monitoring, and human-computer interaction.

# Algorithm
The Person Detector employs the DetectNet algorithm as its core component. DetectNet is a deep learning-based object detection framework that uses convolutional neural networks (CNNs) to detect and localize objects in real-time. Specifically, it is trained to recognize human figures and provide bounding box predictions for each detected person.

# Running the Program
To use the Person Detector, follow these steps:
1. Login into your Nano using IP adress.
2. Using VScode and open /home/nvidia/jetson-inference/python/examples/detectnet.py
3. Run the code ./detectnet.py /dev/video0 newout.mp4

# Image Detection
1. Provide the image file you want to analyze.
2. Execute the program.
3. The Person Detector will process the image and display the results, including the bounding boxes around the detected individuals.

# Video Stream Detection
Connect a camera or provide a video file as input.
Execute the program.
The Person Detector will process the video stream in real-time and display the results, indicating the location of detected people using bounding boxes.
