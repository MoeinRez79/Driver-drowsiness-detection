# Driver Drowsiness Detection


This project implements a Realtime Drowsiness Detection system using computer vision techniques and deep learning. The system utilizes a webcam to capture live video feed, detecting both eyes and faces in each frame to determine the status of the user's eyes – whether they are open or closed.

##
##

## Requirements

**- Python 3.x**

**- OpenCV (cv2)**

**- Numpy**

**- Haar Cascade Classifier for face and eye detection**

**- Trained deep learning model for eye status prediction**

##
##

## Installation

To set up the environment, run the following commands:

      pip install opencv-contrib-python
      pip install numpy

Make sure to download the Haar Cascade Classifier XML files for face and eye detection.

You can find them in the OpenCV GitHub repository: 

    wget https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml
    wget https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_eye.xml


The system will open the webcam, capturing video frames in real-time. It will then analyze the frames to determine the status of the user's eyes and display the result on the screen.

Press 'q' to exit the application.

##
##

## Model Training

The deep learning model used for eye status prediction has been trained on a dataset containing examples of both open and closed eyes. The model is implemented using DeepFace, a deep learning facial recognition and facial attribute analysis library for Python.

##
##

# Output

<img src="https://github.com/MoeinRez79/Driver-drowsiness-detection/blob/main/Live_image_1.png" alt="img1"/>
<img src="https://github.com/MoeinRez79/Driver-drowsiness-detection/blob/main/Live_image_2.png" alt="img2"/>
