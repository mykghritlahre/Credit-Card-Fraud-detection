# Credit-Card-Fraud-detection

## Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset contains transactions made by European cardholders in September 2013. The project is implemented using Jupyter Notebooks and explores deep learning and sampling methods to enhance fraud detection.

## Table of Contents
- Installation
- Usage
- Details of Deep Learning + Sampling.ipynb
  - Data Exploration
  - Pre-processing
  - Model Training and Evaluation
- Contributing
- License
- Contact

## Installation
Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/mykghritlahre/Credit-Card-Fraud-detection.git
cd Credit-Card-Fraud-detection
pip install keras
pip install tensorflow
pip install numpy
pip install pandas


```

## Usage
Open the Jupyter Notebook and run the cells to execute the code. The notebook contains code for data exploration, preprocessing, model training, and evaluation.

```bash
jupyter notebook "Deep Learning + Sampling.ipynb"
```

## Details of Deep Learning + Sampling.ipynb

### Data Exploration
- The dataset contains 284,807 transactions with 31 features.
- There is a significant class imbalance with only 492 fraudulent transactions.
- Initial data exploration includes displaying the first few rows and descriptive statistics of the dataset.

### Pre-processing
- Normalization of the 'Amount' feature using StandardScaler.
- Dropping irrelevant columns for model training.

### Model Training and Evaluation
- The notebook trains a deep learning model using Keras.
- Evaluation metrics include accuracy, precision, recall, and F1-score.
- Visualizations include histograms of numerical columns and correlation with the target variable.

