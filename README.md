Human Pose Estimation using Machine Learning

This repository provides an implementation for Human Pose Estimation, which predicts the location of various human key points (joints and landmarks), such as elbows, knees, necks, shoulders, hips, and chests.

Software Requirements:

Programming Languages: Python
Deep Learning Frameworks: TensorFlow, PyTorch
Libraries: OpenCV, NumPy
Model: OpenPose
Proposed Methodology
System Design

This project leverages BlazePose, a high-performance human pose estimation model optimized for mobile real-time applications. Using a lightweight convolutional neural network, it efficiently detects 33 key body points in images or video frames.

Key Features:

Two-Stage Detector-Tracker Pipeline:
BlazePose adopts a two-step approach where an initial detector identifies the region of interest containing the subject, followed by a tracker that predicts keypoint positions within the detected area.

3D Pose Estimation:
In addition to 2D keypoint recognition, BlazePose provides 3D coordinates, offering a comprehensive analysis of body movements in three dimensions.

Mobile Device Optimization:
Designed with mobile platforms in mind, BlazePose delivers high-performance results while being energy-efficient.


