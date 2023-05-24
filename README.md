# Project Description

## Technical Stack:
  - Language: Python
  - Frameworks & Libraries: PyTorch, NumPy, Pandas, Scikit-learn, Matplotlib
  - Used [Kaggle](https://www.kaggle.com/)'s Jupyter Notebook

## About the Dataset:
- *diabetes.csv* file contains the dataset used in the project.
- Link to the dataset: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
- Source: National Institute of Diabetes and Digestive and Kidney Diseases.
- Objective: to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.
- Constraints (on the selection of these instances from a larger database): ALL patients here are FEMALES at least 21 years old of Pima Indian heritage.
- No NULL values.

### Splitting data for the model:
- original data was split into 85 % training set and 15 % test set using sklearn.
  - <img width="744" alt="image" src="https://github.com/shubhranshu-animesh/diabetes_prediction/assets/77923668/e6079b0d-7bb2-4d43-bad5-c319deee0727">

# About the Model:
- *pima-diabetes-pytorch.ipynb* file contains a Neural Network Model for diabetes prediction.

## Description:
- Implemented a Neural Network Model for classification using PyTorch (a deep learning framework based on the Torch library).
- NN Model contains an Input Layer (with 8 features), 2 Hidden Layers (with 20 units each) and an Output Layer (with 2 units).
- Plot for Loss with each iteration while training is show below: 
  - <img width="500" alt="image" src="https://github.com/shubhranshu-animesh/diabetes_prediction/assets/77923668/e8ccba35-dcb7-440d-8354-28b48abe1741">

## Model Evaluation on test set:
  - Accuracy Score: 0.78
  - Heatmap for confusion matrix:
    - <img width="300" alt="image" src="https://github.com/shubhranshu-animesh/diabetes_prediction/assets/77923668/62fc2082-414f-4e38-997a-fe37c2ef87ca">
  - F1 Score: 0.66
