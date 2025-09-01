# 🛣️ Road Lane Detection Using Python and OpenCV
This project implements a real-time lane detection system using Python, OpenCV, and NumPy. It processes video frames to detect road lanes using edge detection, region masking, and Hough line transformation. Ideal for self-driving car simulations, computer vision practice, or academic projects.

---

## 📁 Project Structure
Road-Lane-Detection/
```│ 
├── input.mp4 # Sample road video for lane detection 
├── solution.py # Main Python script for lane detection
├── venv/ # Virtual environment folder
└── README.md # Project overview and instructions


---
```

### 🚀 How to Run

## 🔧 Step-by-Step Setup

1. Clone this repository  
2. Create a virtual environment:

```bash
python -m venv venv

 Activate the virtual environment:

On Windows:
.\venv\Scripts\activate

On Mac/Linux:
source venv/bin/activate

Install required libraries:
pip install opencv-python numpy


Run the script:
bash
python solution.py
Press q to quit the video window.
```
## 📦 Required Libraries
Library	Purpose
opencv-python	Image processing and video I/O
numpy	Array operations and math

### Install all with:
bash
pip install opencv-python numpy

## 📹 What It Does
Converts each video frame to grayscale

Applies Gaussian blur and Canny edge detection

Masks the region of interest (road area)

Detects lane lines using Hough Transform

Averages and visualizes left/right lane boundaries

Overlays detected lanes on the original video


### 🛠️ Technologies Used
Python
OpenCV
NumPy
VS Code (for development)

