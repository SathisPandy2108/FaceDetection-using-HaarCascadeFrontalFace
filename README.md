
# Face Detection Using Haar Cascades

This project demonstrates real-time face detection using Haar cascade classifiers. It uses OpenCV's pre-trained `haarcascade_frontalface_default.xml` model to detect faces in images or video streams.

## Features
- Real-time face detection using webcam.
- Can detect multiple faces simultaneously.
- Simple and efficient code using OpenCV.

## Prerequisites
- Python 3.9
- OpenCV library

## Installation


1. Install the required dependencies:
   ```bash
   pip install opencv-python
   ```

## Usage

1. Run the face detection script:
   ```bash
   python facedetection.py
   ```

2. The script will activate your webcam and start detecting faces in real time. Press `Esc` to quit the application.

## Code Explanation

- **facedetection.py**: The main script that handles face detection using OpenCV and the Haar cascade model.
- **haarcascade_frontalface_default.xml**: The pre-trained model used for detecting faces.


## Haar Cascade Details

Haar cascades are machine learning-based object detection methods proposed by Paul Viola and Michael Jones in their 2001 paper, "Rapid Object Detection using a Boosted Cascade of Simple Features." OpenCV provides pre-trained models for face detection.

## Customization
To use a different Haar cascade model or detect other objects, replace the `haarcascade_frontalface_default.xml` with a different XML file (e.g., `haarcascade_eye.xml` for eye detection).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

