# OpenCV Security Camera

A beginner-friendly Python security camera project using OpenCV to detect motion through webcam frame differences.

## Features
- Captures video using a webcam.
- Detects differences between consecutive frames.
- Uses grayscale conversion and thresholding.
- Finds contours to identify larger areas of movement.
- Plays a beep sound when motion is detected.

## Technologies Used
- Python
- OpenCV
- winsound

## Requirements
- Python installed on Windows
- OpenCV (`opencv-python`)
- A working webcam

## Installation

Install OpenCV:

```bash
pip install opencv-python