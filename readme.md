# Lane-Line Detection System

This project consists of two files:

1. `GUI.py`: This Python script provides a graphical user interface (GUI) for displaying two videos side by side. It utilizes OpenCV and Tkinter libraries to achieve this functionality.

2. `main.py`: This Python script contains the main algorithm for detecting lane lines in a video stream. It utilizes computer vision techniques such as color thresholding, edge detection, and Hough line transformation.

## Usage

### Step 1: Running the GUI Application

Run the `GUI.py` script to open the GUI application. This GUI displays two videos side by side, typically an input video and its corresponding output video.

```bash
python GUI.py
```

### Step 2: Lane-Line Detection

Run the `main.py` script to perform lane-line detection on a video stream. This script processes each frame of the video, detects lane lines, and overlays them on the original video.

```bash
python main.py
```
## Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy
- Matplotlib
- MoviePy
- Pillow (PIL)
- tkinter

Ensure you have all the required libraries installed before running the scripts.

**Note:** Make sure to have the input and output video files (`input2.mp4` and `output2.mp4`) in the same directory as the scripts before running them.
