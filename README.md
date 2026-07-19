# Face Mask Detection using CNN

A real-time Face Mask Detection system built using **TensorFlow**, **OpenCV**, and **Convolutional Neural Networks (CNN)**.

## Features

- Real-time face detection using OpenCV
- Detects whether a person is wearing a mask
- CNN-based image classification
- Live webcam prediction
- Model trained on more than 9500 images

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## Dataset

- With Mask Images
- Without Mask Images

Total Images: **9536**

## Model

CNN Architecture

- Conv2D
- MaxPooling2D
- Flatten
- Dense
- Dropout
- Sigmoid Output Layer

Validation Accuracy: **95%+**

## Project Structure

```
face-mask-detection-ai/
│
├── dataset/
├── models/
├── notebooks/
├── detect_mask.py
├── train_model.py
├── requirements.txt
└── README.md
```

## Installation

```bash
pip install -r requirements.txt
```

## Run

```bash
python detect_mask.py
```