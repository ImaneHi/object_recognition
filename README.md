# Object Recognition with Fruits 360 Dataset

## Team Members
- Imane HIMMI
- Lamyae RJAFALLAH

## Description
This project focuses on object recognition using the Fruits 360 dataset. It leverages machine learning techniques to classify and identify various fruits. The project demonstrates the application of traditional machine learning algorithms (KNN and Ridge regression) in computer vision tasks, specifically for fruit classification.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)

## Installation
To run this project on your local machine:

1. Clone the repository:
```bash
git clone https://github.com/ImaneHi/object_recognition.git
cd object_recognition
```

Required Python packages:
- scikit-learn
- NumPy
- Pandas
- Matplotlib
- OpenCV

## Usage
1. Open the Jupyter Notebook file (.ipynb) in your Jupyter environment:
```bash
jupyter notebook
```

2. Navigate to the project directory and open the notebook

3. Follow the notebook cells to:
   - Load and preprocess the dataset
   - Extract features from images
   - Train the KNN and Ridge models
   - Evaluate performance
   - Make predictions on new images

## Dataset
The project uses the [Fruits 360 Dataset](https://www.kaggle.com/moltean/fruits), which contains:
- High-quality images of fruits
- Multiple classes of fruits
- Training and test sets
- Various angles and lighting conditions

## Model
The project implements two machine learning algorithms:
1. K-Nearest Neighbors (KNN):
   - Used for classification tasks
   - Finds the k most similar training examples
   - Makes predictions based on majority voting

2. Ridge Regression:
   - Linear regression with L2 regularization
   - Helps prevent overfitting
   - Used for regression tasks

Key features:
- Feature extraction from images
- Hyperparameter tuning
- Cross-validation
- Model evaluation metrics

## Results
The model achieves the following performance metrics:
- Accuracy
- Precision
- Recall
- F1 Score


