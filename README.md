# Breast Cancer Classification Using Single-Layer Perceptron (ANN)

## Project Overview
This project implements an Artificial Neural Network (ANN) using a Single-Layer Perceptron to perform binary classification on the Breast Cancer Wisconsin dataset.

The model predicts whether a tumor is **Benign (B)** or **Malignant (M)** based on different medical features.

The Single-Layer Perceptron is implemented from scratch using Python and NumPy without using pre-built machine learning models.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (for preprocessing and evaluation, if used)

## Dataset
The project uses the Breast Cancer Wisconsin dataset, which contains medical features extracted from breast cancer cell images.

**Classification:**
- 0 – Benign
- 1 – Malignant

## Project Workflow
1. Load the dataset from a CSV file.
2. Preprocess the data.
3. Separate input features and target labels.
4. Split the dataset into training and testing sets.
5. Implement a Single-Layer Perceptron using NumPy.
6. Train the ANN model.
7. Test the model on unseen data.
8. Evaluate performance using classification metrics.

## Model
A Single-Layer Perceptron is used as a basic Artificial Neural Network. It learns weights and bias during training and uses an activation function to classify tumors.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## How to Run
1. Clone this repository.
2. Install the required libraries:
   `pip install numpy pandas matplotlib scikit-learn`
3. Open the Jupyter Notebook.
4. Make sure the CSV dataset is in the correct folder.
5. Run all notebook cells.

## Objective
The objective is to understand the working of an Artificial Neural Network and implement a Single-Layer Perceptron from scratch to solve a real-world binary classification problem.

## Author
Created as an Artificial Neural Network academic project.