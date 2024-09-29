# Drowsiness-Detection-and-Alert
This project is a Drowsiness Detection and Alert System built using Python and computer vision techniques. It detects if a person (typically a driver) is drowsy based on eye blink patterns and generates an alert sound to prevent potential accidents.

## Features
- Real-time monitoring of a person's eyes through the camera feed.
- Detects if the person is drowsy based on eye closure duration.
- Sound alert to wake the person up if drowsiness is detected.
- Lightweight and works efficiently with minimal setup.

## Technologies Used
OpenCV (cv2): For capturing video streams and image processing.
NumPy: For efficient numerical computations.
Imutils: For easier OpenCV functions and handling facial landmarks.
Winsound: To generate alert sounds on Windows systems.

## Installation
## Prerequisites
Python 3.x
cv2 (OpenCV)
numpy
imutils
winsound (for Windows systems)

## How It Works
1. The system captures video from your webcam using OpenCV.
2. Using facial landmark detection, it identifies the eye regions.
3. The system calculates the Eye Aspect Ratio (EAR) to determine whether the eyes are open or closed.
4. If the eyes remain closed for a prolonged period (indicating drowsiness), a sound alert is triggered using winsound.

## Usage
This system can be used in situations where continuous monitoring is needed to prevent drowsiness, such as:
Driver monitoring systems
Long-duration workstation monitoring
Fatigue detection in industrial environments
