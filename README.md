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


## Future Enhancements

There are several opportunities for enhancing the ASL detection model and overall system [As it is not yet Perfect and still faces issues in detecting few alphabets]. Consider the following ideas for future improvements:

1. **Integration with New Datasets:** Explore additional ASL datasets to diversify the training data and improve the model's generalization to different signing styles.

2. **Fine-Tuning Hyperparameters:** Experiment with different hyperparameter settings to optimize the model's performance. This may involve adjusting learning rates, batch sizes, or architecture configurations.

3. **Incorporating Transfer Learning:** Investigate the potential benefits of incorporating transfer learning techniques, leveraging pre-trained models on related tasks to boost performance.

4. **Real-time Feedback Mechanism:** Implement a real-time feedback mechanism to provide users with immediate guidance on improving their sign gestures, enhancing the learning experience.

5. **Multi-modal Integration:** Explore the integration of additional sensor modalities, such as depth sensors or audio cues, to improve the robustness of sign detection in various environments.

**This Repo can also be extended to handle video data**
1. to detect common Hand Gestures used in Sign Language
2. To sign words [Sequence of individual Signed Alphabets]

   
