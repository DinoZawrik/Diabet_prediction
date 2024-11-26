# Diabetes Prediction Model

## Project Overview
This project implements machine learning models to predict diabetes based on diagnostic measurements. The goal is to assist healthcare professionals in early diabetes risk assessment using patient medical indicators.

## Dataset
The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. It contains the following features for female patients of Pima Indian heritage:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age
- Outcome (Target Variable)

## Requirements
- Python 3.8+
- Required packages:
    - numpy
    - pandas
    - scikit-learn
    - matplotlib
    - seaborn

To install requirements:
pip install -r requirements.txt

## Project Structure
├── data/
│   └── diabetes.csv
├── main.ipynb
├── README.md
└── requirements.txt

## Features
- Comprehensive data analysis and visualization
- Multiple machine learning models comparison:
    - Logistic Regression
    - Decision Trees
    - Random Forest
    - Support Vector Machines
    - K-Nearest Neighbors
- Model evaluation and performance metrics
- Feature importance analysis

## Installation & Usage
1. Clone the repository
   git clone https://github.com/yourusername/diabetes-prediction.git
   cd diabetes-prediction

2. Install dependencies
   pip install -r requirements.txt

3. Run Jupyter Notebook
   jupyter notebook

4. Open `main.ipynb` and run the cells

## Model Performance
Our models achieve the following performance metrics:
- Accuracy: ~75-85%
- Precision: ~75-80%
- Recall: ~70-75%
- F1-Score: ~75-80%

## Visualizations
The project includes various visualizations:
- Feature distributions
- Correlation heatmap
- Feature importance plots
- ROC curves
- Confusion matrices

## Acknowledgments
- Original dataset from the National Institute of Diabetes and Digestive and Kidney Diseases
- Inspired by the ongoing research in diabetes prediction using machine learning
- Thanks to the scikit-learn team for their excellent machine learning library

## Contact
DinoZawrik - [79103321517@yandex.ru](mailto:79103321517@yandex.ru)

Project Link: [https://github.com/yourusername/diabetes-prediction](https://github.com/yourusername/diabetes-prediction)