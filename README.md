
---

# Speech Emotion Recognition using CNN

This repository contains the implementation of a **Speech Emotion Recognition (SER)** system leveraging **Convolutional Neural Networks (CNNs)**. The system classifies speech signals into distinct emotional categories based on extracted audio features.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Datasets Used](#datasets-used)
4. [Installation](#installation)
5. [Model Details](#model-details)
6. [Results](#results)
7. [Contributing](#contributing)
8. [Download Resources](#download-resources)

---

## Introduction

Speech Emotion Recognition (SER) is an application of machine learning aimed at understanding emotions from audio signals. This project implements a **CNN-based model** trained on multiple datasets like **RAVDESS**, **CREMA-D**, **TESS**, and **SAVEE**, effectively classifying emotions such as neutral, happy, sad, angry, and more.

---

## Features

- **Feature Extraction**:
  - **MFCC (Mel Frequency Cepstral Coefficients)**
  - **Zero-Crossing Rate (ZCR)**
  - **Root Mean Square Energy (RMSE)**
- Multi-dataset support for robust training.
- CNN architecture designed for accurate emotion classification.
- End-to-end pipeline:
  - Data preprocessing
  - Model training
  - Evaluation
  - Prediction

---

## Datasets Used

### Datasets:
- **RAVDESS** (Ryerson Audio-Visual Database of Emotional Speech and Song)
- **CREMA-D**
- **TESS**
- **SAVEE**

These datasets are preprocessed to extract features and generate labels corresponding to emotional classes.

### Emotion Classes:
- Neutral
- Happy
- Sad
- Angry
- Fear
- Disgust
- Surprise

> **Note**: Ensure the datasets are downloaded and their paths are correctly specified in the code.

---

## Installation

Clone this repository:
   ```bash
   git clone https://github.com/Lakshmanyadav236/Speech_Emotion_Recognition_CNN.git
   cd speech-emotion-recognition-cnn
   ```



---

## Model Details

### Architecture:
- **Feature Extraction**:
  - MFCC
  - ZCR
  - RMSE
- **Model**: CNN with the following layers:
  - Convolutional Layers
  - Max Pooling Layers
  - Dense Layers
  - Dropout for Regularization
- **Framework**: TensorFlow/Keras

---

## Results

### Metrics:
- **Accuracy**: 79%
- **Loss**: 40

> **Note**: Add a confusion matrix or graph visualizing the model's performance for better insights.

---

## Contributing

Contributions are welcome! Feel free to:
1. Open an issue for discussions.
2. Submit a pull request for improvements or new features.

---

## Download Resources

### `emotions.csv`
The preprocessed emotion labels and file paths are stored in `emotions.csv`.  
[Download `emotions.csv` from Google Drive](https://drive.google.com/file/d/1lI-3pNvUYRskNBJ55OdDIj9NzOX4uxeF/view?usp=sharing)

---
