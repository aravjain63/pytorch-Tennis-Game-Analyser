
# pytorch Tennis Game Analyser

## Introduction
This project employs advanced machine learning and computer vision techniques to conduct an in-depth analysis of tennis matches. Utilizing the YOLO algorithm, the system accurately identifies players and the tennis ball within video footage. Additionally, it leverages Convolutional Neural Networks (CNNs) to pinpoint court keypoints, enabling precise measurements of player velocities, ball speeds, and shot counts. This hands-on initiative offers an excellent opportunity to refine skills in machine learning and computer vision.
## Output Videos
Here is a screenshot from one of the output videos:

![Screenshot](output_videos/screenshot.jpeg)
[![Watch the video](output_videos/output_video.avi)
## Models Used for the project
* YOLO v8 for player detection
* Fine Tuned YOLO for tennis ball detection
* Court Key point extraction
## ---------
* Trained YOLOV5 model: https://drive.google.com/file/d/1UZwiG1jkWgce9lNhxJ2L0NVjX1vGM05U/view?usp=sharing
* Trained tennis court key point model: https://drive.google.com/file/d/1QrTOF1ToQ4plsSZbkBs3zOLkVt3MBlta/view?usp=sharing

## Training on google colab:downloads
* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb

## Requirements
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv
