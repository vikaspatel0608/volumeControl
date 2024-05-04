# Volume Control

## Overview

The **volume-control** project implements gesture-based volume control using a combination of hardware and software components. A webcam captures real-time video input, which is processed through OpenCV and Mediapipe to detect and track hand movements using a hand landmark model. The system adjusts the system volume based on the recognized gestures. Numpy is utilized to map the range of distances between the index finger and thumb to the volume range, while math libraries are used to calculate the distance between the index finger and thumb.

## Components

### Hardware:
- Webcam

### Software:
- OpenCV
- Mediapipe
- PyCaw
- Numpy
- Math libraries

## Functionality

The project captures real-time video input from a webcam and processes it to detect hand movements using OpenCV and Mediapipe. Once hand movements are detected, a hand landmark model is employed to track gestures. Based on the recognized gestures, the system adjusts the system volume using PyCaw. Numpy is used to map the range of distances between the index finger and thumb to the volume range, and math libraries are utilized to calculate the distance between the index finger and thumb.

## Installation

1. Clone the repository: `git clone <repository_url>`
2. Install the required dependencies:
   ```bash
   pip install opencv-python mediapipe pycaw numpy
   ```

## Usage

1. Run the program:
   ```bash
   python volume_control.py
   ```
2. Ensure that a webcam is connected and positioned correctly to capture hand movements.
3. Perform hand gestures in front of the webcam to control the system volume.

## Contribution

Contributions are welcome! If you want to contribute to this project, please fork the repository and submit a pull request.
