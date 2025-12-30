# Parts Recognition and Counting System

This repository contains the implementation of a **Parts Recognition and Counting System** developed for a Pattern recognition course. The system is designed to recognize different industrial parts from images and accurately count the number of parts present using computer vision techniques.

---

## Project Overview

Manual stock counting in manufacturing environments is time-consuming and error-prone. This project aims to automate the process by developing a pattern recognition system that:

- Identifies different types of parts from images
- Assigns labels to recognized parts
- Counts the number of parts present in an image

The system is implemented and demonstrated using a **Jupyter Notebook**.

---

## System Workflow

1. Image input (captured using mobile phone or camera)
2. Image preprocessing
3. Feature extraction
4. Part recognition using a machine learning model
5. Parts counting using image processing techniques
6. Output of part label and quantity

---

## Key Features

- Supports recognition of multiple part types
- Handles images with varying lighting, angles, and backgrounds
- Counts parts arranged in different configurations (scattered, grouped, overlapping)
- Uses open-source computer vision libraries for processing and counting

---

## Techniques Used

- Image preprocessing (normalization, grayscale conversion, noise reduction)
- Feature extraction techniques (e.g., PCA or similar methods)
- Machine learning–based classification
- OpenCV-based parts counting algorithms

---

## Dataset

- Images were captured manually by group members
- Multiple images per part with different:
  - View angles
  - Lighting conditions
  - Backgrounds
- Additional images containing multiple parts for counting
- Dataset is not included in this repository

---

## How to Run

1. Ensure Python is installed.
2. Install required libraries:
   - OpenCV
   - NumPy
   - Matplotlib
   - Scikit-learn
3. Open the Jupyter Notebook:
```

jupyter notebook TPR2251_Project.ipynb

```
4. Run the cells sequentially to reproduce the results.

---

## Learning Outcomes

- Practical application of pattern recognition concepts
- Experience with image-based feature extraction
- Implementation of object recognition and counting algorithms
- Handling real-world image variations and noise

---

## Notes

This project is developed for **academic and learning purposes only**. The implementation focuses on demonstrating pattern recognition techniques rather than production-level deployment.
