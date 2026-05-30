# Real-Time-Gender-Age-and-Emotion-Recognition-platform

## Overview

This project is a real-time facial analysis system that detects a person's **emotion, age, and gender** using a webcam feed. The application uses **Computer Vision** and **Deep Learning** techniques to identify faces and generate predictions in real time.

## Features

* Real-time face detection using OpenCV
* Emotion recognition (7 emotions)
* Gender prediction (Male/Female)
* Age estimation
* Live webcam streaming
* Flask-based web interface

## Technologies Used

* Python 3.6
* OpenCV
* TensorFlow
* Keras
* NumPy
* Pandas
* Flask

## Emotion Classes

The system can detect the following emotions:

* Angry
* Disgust
* Fear
* Happy
* Neutral
* Sad
* Surprise

## Project Workflow

1. Capture live video from webcam.
2. Detect faces using Haar Cascade Classifier.
3. Extract and preprocess facial regions.
4. Predict emotion using the trained CNN model.
5. Predict gender using the trained gender model.
6. Predict age using the trained age model.
7. Display results on the video feed in real time

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python run.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## Requirements

```text
Python 3.6
TensorFlow 2.6.0
Keras 2.6.0
OpenCV 4.5.4.60
NumPy 1.19.2
Pandas 1.1.3
```


