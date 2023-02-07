# Simple Facial Recognition with OpenCV and Raspberry Pi 4

This project demonstrates how to implement a simple facial recognition system using OpenCV and Raspberry Pi 4. OpenCV is an open-source computer vision and machine learning library that provides pre-trained algorithms for facial recognition.

## Requirements
- Raspberry Pi 4
- OpenCV
- Haar cascade classifier

## Getting Started

1. Update and upgrade your Raspberry Pi:
    ```bash
    sudo apt-get update
    sudo apt-get upgrade
    ```

2. Install the required libraries:
    ```bash
    sudo apt-get install libjpeg-dev libtiff5-dev libjasper-dev libpng12-dev
    sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
    sudo apt-get install libxvidcore-dev libx264-dev
    sudo apt-get install qt4-dev-tools
    ```

3. Install OpenCV:
    ```bash
    pip install opencv-python
    ```

4. Run the code
    ```bash
        python3 face_detection.py
    ```


