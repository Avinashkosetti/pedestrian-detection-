# Pedestrian-detection-
# Pedestrian Detection Using Gradient-Based Algorithm

## Introduction

Pedestrian detection is a critical task in various applications, including autonomous driving, surveillance, and robotics. This project demonstrates how to detect pedestrians using a gradient-based algorithm with OpenCV in Python.

## Description

The algorithm works by analyzing the gradients of an image. It checks the directly surrounding pixels of every single pixel to determine how much darker the current pixel is compared to the surrounding pixels. The algorithm then draws arrows indicating the direction in which the image gets darker. This process is repeated for every pixel in the image, resulting in a field of arrows called gradients. These gradients reveal the flow of light from light to dark areas, which the algorithm uses for further analysis to detect pedestrians.

## Prerequisites

Before starting this project, ensure you have the following installed:
- Python 3.x
- OpenCV
- Numpy

You can install these libraries using pip:
```bash
pip install opencv-python numpy
