

# Placement Prediction using K-Nearest Neighbors (KNN)

This repository contains a machine learning project aimed at predicting whether a student will be placed based on various features. The project uses a K-Nearest Neighbors (KNN) classifier to train the model.

## Project Overview

The goal of this project is to predict the placement status of students using the K-Nearest Neighbors algorithm. This is a supervised learning problem where we predict whether a student is "placed" (status = 1) or "not placed" (status = 0) based on certain features such as academic performance, work experience, and salary expectations.

## Dataset

The dataset used for training the model contains various features, including:

- **Gender**: Male or Female
- **SSC Percentage**: Secondary Education percentage
- **HSC Percentage**: Higher Secondary Education percentage
- **Degree Percentage**: Undergraduate degree percentage
- **Work Experience**: Whether the student has prior work experience
- **ETest Percentage**: Employment test percentage
- **Specialization**: Field of specialization (e.g., Science, Arts)
- **Salary**: Salary offered upon placement
- **Status**: Placement status (target variable)

## Libraries and Tools

The project uses the following Python libraries:

- `pandas` for data manipulation
- `sklearn` for machine learning algorithms and evaluation
- `matplotlib` for plotting graphs (if included)
- `numpy` for numerical computations

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/saivamsi4514/JOB-ANALYSIS/
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Model Training

The model uses the K-Nearest Neighbors (KNN) algorithm. The steps involved in the model training process are:

1. **Data Preprocessing**: The dataset is cleaned and the target variable (`status`) is separated from the features.
2. **Train-Test Split**: The data is split into training and testing sets using an 80-20 ratio.
3. **Model Training**: A KNN model is trained on the training data using 2 neighbors (`n_neighbors=2`).
4. **Evaluation**: The model's performance is evaluated using a confusion matrix and classification report, showing precision, recall, and f1-score.

## Usage

To use this project:

1. Load the data in the notebook.
2. Train the model by running the cells in sequence.
3. Evaluate the model's performance based on the classification report and confusion matrix.

## Results

The KNN classifier achieved the following performance metrics on the test set:

- **Accuracy**: 100%
- **Precision, Recall, F1-Score**: 100% for both placed and non-placed categories.

## Author
- CH.SAI VAMSI

##License
This project is licensed under the MIT License.

