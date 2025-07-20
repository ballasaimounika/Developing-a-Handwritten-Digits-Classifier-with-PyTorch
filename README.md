# Handwritten Digits Classifier with PyTorch

This project demonstrates the implementation of a Convolutional Neural Network (CNN) using PyTorch to classify handwritten digits from the MNIST dataset—a widely used benchmark in computer vision.

> This was the second project of the **Udacity Machine Learning Fundamentals Nanodegree** offered by AWS under the **AWS AI & ML Scholarship** program.

## Project Overview
The objective of this project is to build a deep learning model that accurately classifies grayscale images of handwritten digits (0–9) from the MNIST dataset. A CNN model is built and trained using PyTorch and evaluated for its accuracy.

### Key Steps:
1. Load and preprocess the MNIST dataset
2. Visualize and explore the data
3. Build and train a CNN using PyTorch
4. Evaluate model performance
5. Save and reload the trained model
6. Perform inference on new digit images
7. Analyze predictions using a confusion matrix

**Achieved Accuracy:**
The trained model achieved an accuracy of 91.89% on the test set.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/ballasaimounika/Developing-a-Handwritten-Digits-Classifier-with-PyTorch.git
   
   cd Developing-a-Handwritten-Digits-Classifier-with-PyTorch
   ```
   
2. Create and activate a virtual environment (optional but recommended):
   ```
   python -m venv venv
   
   source venv/bin/activate # On Windows: venv\Scripts\activate
   ```
   
3. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
