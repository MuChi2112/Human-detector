# Person Detector

# Introduction
The Person Detector is an AI-powered project that utilizes the DetectNet algorithm to detect and locate people in images or video streams. It leverages deep learning techniques and computer vision to accurately identify human figures with the help of Jetson Nano Kit. This project aims to assist in various applications, including surveillance systems, crowd monitoring, and human-computer interaction.

# Algorithm
The Person Detector employs the DetectNet algorithm as its core component. DetectNet is a deep learning-based object detection framework that uses convolutional neural networks (CNNs) to detect and localize objects in real-time. Specifically, it is trained to recognize human figures and provide bounding box predictions for each detected person.

# Running the Program
To use the Person Detector, follow these steps:
1. Open VScode using the IP Adress that was found by using SSH into Nano
2. In the same directory as the Python file "detectnet.py", upload images and videos that you would like to process

Depending on whether it is an image or a video or live feed run the commands as shown below:

# Image and Video Detection
1. Provide the image file you want to analyze.
2. Execute the program with the following command:
    (a)python3 detectnet.py (input.jpg) (output.jpg)
    (b)pyhton3 detectnet.pt (input.mp4) (output.mp4)
4. The Person Detector will process the image and display the results, including the bounding boxes around the detected individuals.

# Video Stream Detection
1. Connect a camera or provide a video file as input.
2. Execute the program with the following command - 
3. The Person Detector will process the video stream in real-time and display the results, indicating the location of detected people using bounding boxes.
