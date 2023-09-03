# Smile Detection Using OpenCV

This is a Python script that utilizes OpenCV to detect faces, eyes, and smiles in a webcam feed. It applies Haar cascades to detect these features and draws rectangles around them in real-time.

## Prerequisites

- Python 3.x
- OpenCV 4.x

## Installation

1. Clone the repository:
   git clone

2. Install the required dependencies:
   pip install opencv-python

3. Download the Haar cascade XML files for face, eye, and smile detection and place them in the project directory.

- [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
- [haarcascade_eye.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_eye.xml)
- [haarcascade_smile.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_smile.xml)

## Usage

1. Run the script:
   python smile_detection.py

2. The webcam feed will open in a new window, and the script will start detecting faces, eyes, and smiles in real-time.

3. Press 'q' to exit the application.

## Customization

- Scaling factors and minimum neighbors for face, eye, and smile detection can be adjusted in the `detect_faces()`, `detect_eyes()`, and `detect_smiles()` functions, respectively.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please create an issue or submit a pull request.
