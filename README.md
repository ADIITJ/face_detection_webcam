# Face Detection


## Description

Face Detection is a Python script that uses OpenCV's pre-trained face cascade to detect faces in real-time using a webcam. It draws rectangles around the detected faces, providing a visual representation of face detection.

## Features

- Real-time face detection using a webcam
- Drawn rectangles around the detected faces
- Simple and easy-to-understand Python code


## Dependencies

To run this code, you need the following dependencies installed:

- Python 3.x
- OpenCV (cv2) library

You can install the OpenCV library using pip:

```shell
pip install opencv-python
```

## Usage

```shell
# Connect a webcam to your computer.

# Clone this repository or download the `face_detection.py` file.

# Open a terminal or command prompt and navigate to the directory containing the `face_detection.py` file.

# Run the script by executing the following command:
python face_detection.py

# A window named "Face Detection" will open, showing the webcam feed with detected faces outlined by rectangles.

# Press 'q' to stop the program and close the window.

```

## Credits

The face cascade used for face detection is a pre-trained model from OpenCV. The `haarcascade_frontalface_default.xml` file is included in OpenCV's data directory.


