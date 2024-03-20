# Face Detection using OpenCV

This repository contains a simple Python script for real-time face detection using OpenCV. It captures video from a webcam and detects faces in each frame, drawing rectangles around them.

## Prerequisites

- Python 3.x
- OpenCV library (`opencv-python`)

## Installation

1. Install the required Python libraries:

```bash
pip install opencv-python
```

## Usage

1. Navigate to the cloned directory:

```bash
cd face-detection
```

2. Run the Python script:

```bash
python face_detection.py
```

3. The script will open up your webcam and start detecting faces in real-time. Press 'q' to exit the program.

## Script Explanation

The script performs the following steps:

1. Import the OpenCV library.
2. Load the pre-trained face detector (`haarcascade_frontalface_default.xml`).
3. Initialize the webcam.
4. Continuously capture frames from the webcam.
5. Convert each frame to grayscale.
6. Detect faces in the grayscale frame using the pre-trained face detector.
7. Draw rectangles around the detected faces.
8. Display the resulting frame with face rectangles.
9. Exit the loop if 'q' is pressed.
10. Release the webcam and close all OpenCV windows.


# Face Recognition System

This repository contains a Python script for building and evaluating a face recognition system using machine learning algorithms.

## Dataset

The Olivetti Faces dataset is used for training and testing the face recognition system. This dataset consists of 400 grayscale images of 40 distinct subjects, with each subject having 10 different images.

## Prerequisites

- Python 3.x
- TensorFlow
- scikit-learn
- matplotlib
- seaborn

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/face-recognition.git
```

2. Install the required Python libraries:

```bash
pip install numpy tensorflow scikit-learn matplotlib seaborn
```

## Usage

1. Navigate to the cloned directory:

```bash
cd face-recognition
```

2. Run the Python script:

```bash
python face_recognition.py
```

3. The script will load the Olivetti Faces dataset, preprocess the data, train machine learning models for face recognition, and evaluate their performance.

## Machine Learning Models

The following machine learning models are trained and evaluated for face recognition:

- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Linear Discriminant Analysis (LDA)
- Logistic Regression
- Naive Bayes
- Decision Tree

## Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report


