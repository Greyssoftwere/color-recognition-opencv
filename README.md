# Color Recognition using OpenCV

## Project Description

This project is a real-time color recognition system developed using Python and OpenCV. It detects colored objects through a webcam and displays a bounding box with the detected color name.

## Features

- Real-time webcam color detection
- Detects Red, Green, and Blue colors
- Draws a bounding box around detected objects
- Displays the detected color name on the screen

## Technologies Used

- Python 3
- OpenCV
- NumPy


## Installation

1. Install the required libraries:

```bash
pip install -r requirements.txt
```

2. Run the program:

```bash
python main.py
```

## How It Works

- Opens the webcam.
- Converts each frame from BGR to HSV color space.
- Detects Red, Green, and Blue objects.
- Draws a rectangle around detected objects.
- Displays the color name above the object.

## Results

<img width="1313" height="821" alt="Screenshot 2026-07-23 014044" src="https://github.com/user-attachments/assets/48e51020-1a2f-4562-9aa2-d639960c59be" />
<img width="1217" height="760" alt="Screenshot 2026-07-23 014126" src="https://github.com/user-attachments/assets/f92b6ea3-dd26-4b9e-958a-c83e4778188e" />
<img width="1300" height="786" alt="Screenshot 2026-07-23 014056" src="https://github.com/user-attachments/assets/a7166c93-f475-4857-b918-06842e34103a" />



