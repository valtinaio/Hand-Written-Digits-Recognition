# Hand-Written-Digits-Recognition
Recognizing handwritten digits using different classification algorithms (Random Forest, Gradient Boosting,...)

## Project Overview
This project implements a Machine Learning model capable of recognizing and classifying handwritten digits (0-9). 

The `digits_recognition.ipynb` notebook demonstrates the complete Data Science workflow: from loading the image data and visualizing samples to training a classifier and evaluating its performance on unseen data.

## The Dataset
The dataset consists of images of handwritten digits from 10 classes, representing the digits `0` through `9`. These images are grayscale and have been resized to a standard size (e.g., 28x28 pixels).
The dataset has been purposely modified to include some **unlabeled images**, **noisy samples**, and **synthetically augmented data** for certain classes. I will  clean the data, handle the noise, and ensure that the dataset is ready for effective model training.  
The dataset used is not provided on this github repository.

## Key Features & Workflow

### 1. Data Visualization
Before training, we visualize the data to understand the input.

### 2. Preprocessing
* **Flattening:** Converting 2D image matrices (8x8) into 1D feature vectors (length 64).
* **Splitting:** Dividing the data into **Training** (to teach the model) and **Testing** (to validate performance) sets.

### 3. Model Training
We use different **Supervised Learning** algorithms (e.g., Random Forest) to learn the patterns associated with each digit.

### 4. Evaluation
The model's performance is analyzed using:
* **Accuracy Score:** The percentage of correctly classified digits.
* **Confusion Matrix:** To see which numbers are most often confused with each other.
* **Classification Report:** Precision, Recall, and F1-Score for each digit.
-> An acurracy of > 97% was acchievved.

## Requirements
See requirements.txt
