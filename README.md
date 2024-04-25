# Change Detection

<p align="center">
<img src = "utils/result.gif"</img>
</p>


## Overview
The Change Detection is a Jupyter notebook designed to explore change detection across a series of images using four distinct algorithms. Each algorithm progressively builds on the previous to enhance detection accuracy and adaptability. By analyzing different methods, users can understand the strengths and limitations of various approaches, including static and adaptive background models, and dual-threshold techniques for detecting and updating changes in real-time.

## Features
- **Four Progressive Algorithms**: Begins with a simple static background model and advances to more complex models incorporating dual thresholds and adaptive updates.
- **Dynamic Background Calculation**: Utilizes the initial set of images to establish a baseline background, which can be static or adaptively updated.
- **Dual Threshold Change Detection**: Enhances change detection sensitivity by using a primary threshold for identifying significant changes and a secondary threshold for background updates.
- **Adaptive Background Update**: Incorporates a feedback mechanism to continually refine the background model based on new image data, focusing on regions without significant changes.

## Requirements
To run this project, you need Python installed on your system along with the following Python libraries:
- NumPy
- OpenCV-Python
- Scikit-Image

You can install these libraries using pip:
```bash
pip install numpy opencv-python scikit-image
```
