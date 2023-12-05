# Face Detection using OpenCV
This repository contains a simple Python script for real-time face detection using OpenCV. The script captures video from the default camera, detects faces in each frame, and draws rectangles around the detected faces.

Prerequisites
- Python
- OpenCV (cv2)

## How to Run
1 Install the required dependencies:
````
pip install opencv-python
````
2 Download the pre-trained Haar Cascade classifier XML file (haarcascade_frontalface_default.xml) from the OpenCV GitHub repository.

3 Save the XML file in the same directory as the script.

4 Run the script:
````
python face_detection.py
````
5 Press ``Esc`` to exit the application.

## Explanation
The script uses the OpenCV library to capture video from the default camera (cv2.VideoCapture(0)).

It loads the Haar Cascade classifier for frontal faces.

In each frame, it converts the image to grayscale and uses the detectMultiScale function to detect faces.

Detected faces are outlined with green rectangles.

The script continues to run until the Esc key is pressed.

----------------------


Feel free to modify and extend the script for your specific use case or integrate it into other projects.
