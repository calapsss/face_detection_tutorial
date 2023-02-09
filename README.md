# Simple Facial Recognition with OpenCV and Raspberry Pi 4
This repository contains a simple facial recognition system using OpenCV and Raspberry Pi 4. The system uses the Haar cascade classifier for facial detection and the Raspberry Pi's Picamera for video capture.
The full tutorial is in https://blog.devgenius.io/effortlessly-build-your-own-facial-recognition-system-with-opencv-and-raspberry-pi-4-a-adccba92e6bb


## Prerequisites
Raspberry Pi 4
Picamera
OpenCV

## Installation
Check that your Picamera is working properly by running the following command:
```libcamera-hello```

Update and upgrade your Raspberry Pi by running the following commands:
```
sudo apt-get update
sudo apt-get upgrade
```

Install the required libraries by running the following command:
```
sudo apt-get install libjpeg-dev libtiff5-dev libjasper-dev libpng12-dev
sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
sudo apt-get install libxvidcore-dev libx264-dev
sudo apt-get install qt4-dev-tools
```
Install OpenCV by running the following command:
```
pip install opencv-python
```

## Usage
Clone the repository by running the following command:
```
git clone https://github.com/calapsss/face_detection_tutorial.git
```

Run the code by using the following command:
```
python face_detection_tutorial.py
```

## Conclusion
With this project, you can now build your own facial recognition system and get a hands-on experience in computer vision and machine learning. If you encounter any issues or have any questions, feel free to reach out to us through the GitHub repository. Our team will be happy to assist you in resolving any issues and answering any questions you may have.

## License
This project is licensed under the MIT License.