AI_mouse Using OpenCV ___________________________________________

In this project we will be using the live feed coming from the webcam to create a virtual mouse using hand tracking.

Description:

In this project, my hand serves as a virtual mouse that can perform all mouse-like functions without ever touching your computer. 
My computer's webcam is being used to find my hands. It will then create a bounding box around my hand and focus on two fingers: 
The fore finger and the middle finger. 
The fore finger will act as a cursor and moving it around, we will be moving the cursor around. 
Now, inorder to successfully click using hand tracking, it is detecting the distance between the fore finger and the middle finger. 
If they are joined together, then it will perform a click. After this a smoothness factor was added as the movement.

Requirements:

# OpenCV
# Mediapipe
# Autopy

OpenCV:
OpenCV is a huge open-source library for computer vision, machine learning, and image processing. 
OpenCV supports a wide variety of programming languages like 
Python, C++, Java, etc. It can process images and videos to identify objects, faces, or even the handwriting of a human.
It can be installed using "pip install opencv-python"

Mediapipe:
MediaPipe is a framework for building multimodal (eg. video, audio, any time series data), cross platform (i.e Android, iOS, web, edge devices) 
applied ML pipelines.
It can be installed using "pip install mediapipe"

Autopy:
AutoPy is a simple, cross-platform GUI automation library for Python. It includes functions for controlling the keyboard and mouse, 
finding colors and bitmaps on-screen, and displaying alerts.
It can be installed using "pip install autopy"
