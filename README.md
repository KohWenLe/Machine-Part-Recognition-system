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

1. Image input (captured using mobile phone)
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

- Multiple images per part with different:
  - View angles
  - Lighting conditions
  - Backgrounds
- Additional images containing multiple parts for counting

---

## How to Run

### Step 1: Create and Activate a Virtual Environment (optional)

Open **Command Prompt** in the project directory:

```bash
python -m venv venv
venv\Scripts\activate
```

---

### Step 2: Install Required Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

### Step 3: Run the Jupyter Notebook

```bash
jupyter notebook
```

Then open and run:

```
Machine Part recognition and counting (training and tkinter).ipynb
```

Run the cells sequentially to reproduce the results.


<img width="500" height="523" alt="image" src="https://github.com/user-attachments/assets/efd2a524-07a7-4b4c-ad48-b7a42e3cc7ca" />


---

## Learning Outcomes

- Practical application of pattern recognition concepts
- Experience with image-based feature extraction
- Implementation of object recognition and counting algorithms
- Handling real-world image variations and noise

---

## Notes

This project is developed for **academic and learning purposes only**. The implementation focuses on demonstrating pattern recognition techniques rather than production-level deployment.
