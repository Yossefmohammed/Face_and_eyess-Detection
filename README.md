# Face and Eyes Detection

This repository contains two Jupyter notebooks demonstrating real-time face and eye detection using OpenCV and Haar Cascade Classifiers.

## Notebooks

### 1. face and eye detection with cascade classifier.ipynb
- **Description:**
  - Detects both faces and eyes in real-time from webcam video stream.
  - Draws rectangles around detected faces and eyes, and labels them.
- **How it works:**
  - Uses OpenCV's pre-trained Haar Cascade classifiers for face and eye detection.
  - Press `q` to quit the video stream.

### 2. face-detection _with cascade-calssifier.ipynb
- **Description:**
  - Detects faces only (no eye detection) in real-time from webcam video stream.
  - Applies Gaussian blur to the grayscale image before detection for improved accuracy.
  - Draws rectangles around detected faces.
  - Press `q` to quit the video stream.

## Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- Jupyter Notebook

## Installation
1. Install Python 3.x from [python.org](https://www.python.org/).
2. Install required packages:
   ```bash
   pip install opencv-python jupyter
   ```
3. (Optional) Create and activate a virtual environment for isolation.

## Usage
1. Clone this repository or download the files.
2. Open a terminal in the project directory.
3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open either notebook and run all cells. Make sure your webcam is connected.

## Notes
- The detection uses your computer's webcam (device 0 by default).
- Press `q` in the video window to stop the detection and close the window.
- You can adjust detection parameters (like scale factor, minNeighbors) in the code for different results.

## References
- [OpenCV Documentation](https://docs.opencv.org/)
- [Haar Cascade Classifier](https://docs.opencv.org/4.x/d7/d8b/tutorial_py_face_detection.html)
