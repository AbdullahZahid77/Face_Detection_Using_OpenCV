# Face_Detection_Using_OpenCV

This repository contains an implementation of a face detection system using OpenCV's Haar Cascade Classifier. The project demonstrates how to detect faces in images and videos efficiently using traditional computer vision techniques.

## Features
- Real-Time Face Detection: Detect faces in images and live video streams using a pre-trained Haar Cascade Classifier.
- Multi-Scale Detection: Automatically detect faces at different scales, making the system robust to varying face sizes and distances from the camera.
- Customizable Parameters: Fine-tune detection accuracy by adjusting parameters like scaleFactor, minNeighbors, and minSize to reduce false positives.
- Simple and Efficient: Designed for high performance, making it suitable for real-time applications on devices with limited computational power.

## Customization
- Adjust the detection parameters in detect_faces.py:
- scaleFactor: Controls the scale of image reduction.
- minNeighbors: Determines the number of neighbors each detection needs to be retained.
- minSize: Sets the minimum size of detected faces.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs, features, or improvements.
