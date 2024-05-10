# Perovskites Stability Prediction
This repository contains a Python script for predicting the stability of perovskite materials using machine learning techniques. The script utilizes materials data from the Materials Project database and employs a RandomForestClassifier model for prediction.

## Requirements
- Python
- NumPy
- Pandas
- Scikit-learn
- Matminer
- mp-api

## Installation
To run the script, make sure you have all the required dependencies installed. You can install them using pip:

```bash
pip install numpy pandas scikit-learn matminer
```

## Usage
1. First, obtain an API key from the Materials Project (MP) [website](https://next-gen.materialsproject.org/).
2. Replace my API key with your own API key in the notebook.
3. Run the required modules in the notebook.

## Description
The notebook performs the following steps:
1. Retrieve perovskite materials data from the Materials Project database using the MP-API.
2. Preprocess the data to extract relevant features.
3. Train a RandomForestClassifier model to predict the stability of perovskite materials.
4. Optimize hyperparameters using GridSearchCV.
5. Evaluate the model's performance on training and testing data.

## Output
These are the outputs of the notebook:
- Best hyperparameters found during grid search.
- Best F1 score achieved during grid search.
- Accuracy on training and testing data.
- F1 score for the training and testing set.
- Confusion matrix for reference.

## Note
Ensure you have appropriate permissions to access the Materials Project database using the provided API key.
