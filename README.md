# SignoLingo

## American Sign Language Detection

## Overview

This repository contains code and resources for an American Sign Language (ASL) detection system. The project utilizes neural networks, OpenCV, and MediaPipe for real-time detection and recognition of ASL signs.

## Features

- Real-time detection of ASL signs.
- Integration with neural networks for accurate sign recognition.
- Utilizes OpenCV for computer vision tasks.
- Leverages MediaPipe for Hand Tracking and Hand Landmark Data generation.

## Dataset
The Dataset Used to train the Model can be found at 

[American Sign Language Dataset](https://www.kaggle.com/datasets/kapillondhe/american-sign-language)
## Prerequisites

Before running the project, make sure you have the following dependencies installed:

- Python 
- OpenCV 
- MediaPipe
- Pandas
- Numpy
- Tensorflow
- Mediapipe
- Matplotlib
- SciKit Learn

## Installation

1. Clone the repository:
   ```bash
   [git clone https://github.com/your-username/your-asl-detection-repo.git](https://github.com/AlterHoodie/SignoLingo.git)
   cd SignoLingo
2. Save the two folders `test` and  `train` from the Downloaded Dataset in a Folder called `ASL_Dataset`
***
<p align='center'>You can Either directly run the SignoLingo.py File to play around with the Model, trying out various alphabet signs</p>

<p align='center'><b>OR</b></p>

<p align='center'>If You are Curious about the Model Workings and Architecture, Check out the model_creation.ipynb file</p>

## Working of SignoLingo.py

1. Use Your Left Hand to Sign Alphabets
2. Keep Your Hand Sufficiently Close enough to the Camera
3. Few Letters You Can Try

| A                                   | B                                   | Y                                           | F                                           |
| ----------------------------------- | ----------------------------------- | ------------------------------------------- | ------------------------------------------- |
| <img src="https://www.lifeprint.com/asl101/fingerspelling/abc-gifs/a.gif" alt="Example Image" width="200" height="200"> | <img src="https://www.lifeprint.com/asl101/fingerspelling/abc-gifs/b.gif" alt="Example Image" width="200" height="200"> | <img src="https://www.lifeprint.com/asl101/fingerspelling/abc-gifs/y.gif" alt="Example Image" width="200" height="200"> | <img src="https://www.lifeprint.com/asl101/fingerspelling/abc-gifs/f.gif" alt="Example Image" width="200" height="200"> |  

   
