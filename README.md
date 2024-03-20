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

