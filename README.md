# FaceDetectionTimeline
This repository contains a Python project that focuses on face detection and recognition in videos, generating a timeline of recognized faces. The project utilizes the OpenCV and OpenFace libraries for face detection and recognition, respectively.

## Project Overview
The project consists of the following main components:

### 1. Known Faces Encoding
**'import dlib'** and **'import numpy'** as np for known faces encoding.
Utilizes the dlib library for face detection and shape prediction.
Uses OpenFace to encode known faces and store their facial features.
### 2. Extract Frames from Video
**'import cv2'**, **'import math'**, and **'import os'** for frame extraction from a video.
Extracts frames from a given video at a specified frame rate and saves them in an output directory.
### 3. Face Detection and Recognition
**'import cv2'**, **'import face_recognition'**, and **'import os'** for face detection and recognition.
Detects faces in the extracted frames using the OpenCV deep learning module.
Compares face encodings of detected faces with known face encodings to recognize familiar faces.
Draws bounding boxes around recognized faces and displays their names on the frames.
### 4. Basic Timeline Generation
**'import math'** and **'from tabulate import tabulate'** for generating a basic timeline.
Prompts the user to input the video duration.
Calculates the total frames, frame rate, and time intervals for the timeline.
Associates recognized faces with the corresponding time intervals and displays the timeline in tabular format.
## Instructions
Install the required libraries and dependencies mentioned in the code.
Set up the necessary data files, including the pre-trained models and known face encodings.
Run the code and follow the prompts to input the video duration.
View the generated timeline that displays the recognized faces within specific time intervals.
Feel free to explore and customize the code according to your specific requirements.

Note: Make sure to comply with the licenses of the utilized libraries and pre-trained models.

#### Enjoy exploring the FaceDetectionTimeline project!
