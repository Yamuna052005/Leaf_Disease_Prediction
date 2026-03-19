# Plant Disease Detection System using Deep Learning

## Overview
This project is a deep learning-based web application that detects plant leaf diseases from images. It uses a trained Convolutional Neural Network (CNN) model to classify plant leaves into different categories.

The system is built with Streamlit for the user interface and TensorFlow/Keras for model prediction.

---

## Problem Statement
Plant diseases significantly reduce agricultural productivity. Early detection is crucial, but manual identification requires expertise and is time-consuming.

Challenges:
- Farmers may not recognize diseases early
- Lack of accessible diagnostic tools
- Manual inspection is inefficient

---

## Solution
This system automates plant disease detection using image classification.

- User uploads a leaf image
- Model analyzes the image
- System predicts disease category instantly

---

## Features
- Image upload interface
- Real-time disease prediction
- Simple and user-friendly UI
- Supports multiple disease classes

---

## Technology Stack

### Frontend
- Streamlit

### Backend / ML
- TensorFlow
- Keras
- NumPy

### Other Tools
- PIL (Image Processing)
- gdown (Model download support)

---

## Model Details
- Model Type: Convolutional Neural Network (CNN)
- Input Size: 128x128 pixels
- Output Classes:
  - Early Blight
  - Healthy
  - Late Blight

---

## How It Works

1. User uploads an image of a plant leaf
2. Image is resized to 128x128
3. Converted into array format
4. Passed to trained CNN model
5. Model predicts the class
6. Result is displayed on screen

---

## Installation & Setup

### Create Virtual Environment
python -m venv venv
venv\Scripts\activate

### Install Dependencies
pip install -r requirements.txt

### Run Application
streamlit run app.py

---

## Usage
- Open the app in browser
- Go to "Disease Recognition"
- Upload a leaf image
- Click "Predict"
- View the result

---

## Limitations
- Works only on trained classes (Early Blight, Healthy, Late Blight)
- Accuracy depends on image quality
- No real-time field validation
- Model reloads on each prediction (inefficient)

---

## Future Improvements
- Add more disease classes
- Optimize model loading
- Deploy using cloud (AWS / GCP)
- Add treatment suggestions
- Improve accuracy with larger dataset

---

## Project Value
- Demonstrates practical use of CNN in agriculture
- Shows integration of ML model with web app
- Useful for early disease detection in crops
