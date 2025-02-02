Drowsiness Detection & Hand Tracking Projects

Overview

This repository contains three Python-based projects utilizing OpenCV, MediaPipe, and Pygame:

Drowsiness Detector - A real-time eye-tracking system that detects drowsiness and triggers an alert.

Hand Tracking - A system that tracks hand landmarks and detects gestures using MediaPipe.

Gesture Control - A project that enables volume control and other actions based on hand gestures.

Project 1: Drowsiness Detector

Description

The Drowsiness Detector identifies signs of fatigue using real-time face and eye tracking. If drowsiness is detected, an alert sound is played.

Technologies Used

OpenCV for image processing

MediaPipe Face Mesh for facial landmark detection

Pygame for alerts and GUI rendering

NumPy for numerical operations

How It Works

Captures real-time video feed using OpenCV.

Detects facial landmarks and measures eye aspect ratio.

If the eyes remain closed for a set duration, an alert is triggered.

Running the Project

pip install opencv-python mediapipe pygame numpy
python Drowsiness_detector.py

Project 2: Hand Tracking

Description

This project detects hand landmarks in real-time and tracks their positions using MediaPipe Hands.

Technologies Used

OpenCV for video capture

MediaPipe Hands for hand landmark detection

Time module for calculating FPS

How It Works

Captures video from the webcam.

Identifies and tracks hand key points.

Displays real-time FPS and hand landmark connections.

Running the Project

pip install opencv-python mediapipe
python HandTrackingCode.py

Project 3: Gesture Control

Description

The Gesture Control System allows users to control volume based on hand movements.

Technologies Used

OpenCV for video capture

MediaPipe Hands for gesture detection

NumPy & Math for distance calculations

How It Works

Detects the position of the thumb and index finger.

Maps the distance between fingers to a volume scale.

Displays visual feedback based on hand movement.

Running the Project

pip install opencv-python mediapipe numpy
python project_code.py

Contributing

Feel free to contribute by submitting pull requests or reporting issues!
