# Herbamate Dataset Prediction - Neural Network Model

This project involves building a machine learning model using a dataset to predict the herbs based on symptoms. The model is built using a neural network approach with TensorFlow and Keras.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Setup and Installation](#setup-and-installation)
4. [Data Preprocessing](#data-preprocessing)
5. [Model Building](#model-building)
6. [Training the Model](#training-the-model)
7. [Model Evaluation](#model-evaluation)
8. [Results](#results)
9. [License](#license)

## Project Overview

This project aims to predict the the herbs based on symptoms experienced by users. The model is built using a Neural Network implemented in TensorFlow/Keras.

### Key Steps:
1. Data Preprocessing: Clean, process, and prepare the data.
2. Model Building: Create a neural network model using Keras.
3. Model Training: Train the model using the training dataset and validate its performance.
4. Model Evaluation: Evaluate the model using test data and various metrics such as R-squared, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

## Dataset Description

The dataset contains information on herbamate products, including:
- Symptoms: The list of symptoms that the user is experiencing.
- Herbs: The herbs used in the product.
- Usage Method: How the herbamate is consumed.
- Relevance Score: A numerical score representing the relevance of the herbs to the symptoms.

### Dataset Format:
The dataset is in CSV format and includes columns like:
- `herbs`: List of herbs used.
- `usage_method`: How the herbamate is consumed.
- `symptoms`: Comma-separated list of symptoms.
- `relevance_score`: A numeric score representing the relevance of the herbs to the symptoms.

## Setup and Installation

### Prerequisites:
- Python 3.x
- TensorFlow
- Pandas
- NumPy
- scikit-learn
- Matplotlib

### Install Dependencies:
To install the required packages, run:

```bash
pip install tensorflow pandas numpy scikit-learn matplotlib
