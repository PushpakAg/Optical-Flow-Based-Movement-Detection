# Optical-Flow-Based-Movement-Detection

## Overview

This project implements a computer vision technique to detect motion between consecutive frames using dense optical flow.

## Key Features

- Preprocesses images by converting them to grayscale and applying Gaussian blur.
- Computes dense optical flow using the Farneback algorithm.
- Generates and visualizes a motion mask based on optical flow magnitude.
- Detects contours and filters bounding boxes around moving regions.
- Applies non-maximum suppression to refine bounding boxes.
- Visualizes the detected movements on the original frames.

## Dataset

- The dataset used here is M-30-HD (1.7GB) (1200x720) 
- We can also use M-30 (290MB) (800x480)
- [M-30-HD](https://universidaddealcala-my.sharepoint.com/:u:/g/personal/gram_uah_es/ERVzfHbeq6JEplBycRHF6akBj4_9j6_hAKzCNVT6fKO0ug?&Download=1)   [M-30](https://universidaddealcala-my.sharepoint.com/:u:/g/personal/gram_uah_es/EZueCuaiFVZKlZZGRcJxpasB2xnaxDPm2MIKi9LQHROSMA?&Download=1)
