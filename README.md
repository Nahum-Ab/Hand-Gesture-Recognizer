# Hand Gesture Recognition Project

## Overview

This project implements a hand gesture recognition system using Convolutional Neural Networks (CNNs). The system is capable of recognizing various hand gestures in real-time using a webcam. It is designed to facilitate intuitive user interaction for applications such as sign language interpretation, gaming, and accessibility features.

## Features

- Real-time hand gesture recognition using a webcam.
- Robust model trained on a dataset of hand gestures.
- Data augmentation techniques to improve model performance.
- Error handling for missing or corrupted images.

## Installation

To set up the project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Nahum-Ab/hand-gesture-recognition.git
   cd hand-gesture-recognition
   ```
2. **Install Required Packages**:
   ```bash
   pip install numpy opencv-python keras tensorflow scikit-learn
   ```

## Usage

1. **Prepare the Dataset**:
   Ensure your dataset is structured correctly.
2. **Real-Time Gesture Recognition**:
   Execute the script to train the model and run the Real-Time Gesture on your dataset.
   ```bash
   python main.py
   ```
   *Press 'q' to exit the webcam feed.*
