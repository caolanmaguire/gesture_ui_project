# Gesture UI - Machine Learning Classifier Comparison

## Project Overview
This project focuses on training and evaluating different classification algorithms on a given dataset. The objective is to compare three classifier models and select the most suitable one for deployment. The classification task can be performed on one of the following datasets:

1. **Human Activity Recognition (HAR)** - Smartphone sensor data for activity classification.
2. **Fashion-MNIST** - A dataset of 70,000 grayscale images of fashion items.

## Dataset Options
- **HAR Dataset**: Includes accelerometer and gyroscope readings from 30 volunteers performing six activities (walking, walking upstairs, walking downstairs, sitting, standing, laying).
- **Fashion-MNIST Dataset**: Contains images of various clothing items such as T-shirts, trousers, coats, and shoes.

## Objectives
- Preprocess the dataset (handling missing values, feature scaling, encoding labels, etc.).
- Train three classification algorithms (e.g., SVM, Logistic Regression, k-NN, Random Forest).
- Compare model performance using cross-validation and evaluation metrics.
- Select the best-performing model based on the results.

## Project Structure
```
├── data/                  # Dataset files
├── notebooks/             # Jupyter Notebooks for analysis and training
├── src/                   # Python scripts for data processing and model training
├── results/               # Model evaluation reports and visualizations
├── README.md              # Project documentation
└── requirements.txt       # Dependencies for the project
```

## Methodology
1. **Data Preprocessing**
   - Cleaning and handling missing data
   - Feature scaling and transformation
   - Encoding categorical variables
   - Addressing class imbalances if necessary

2. **Model Training**
   - Train three classification models
   - Use hyperparameter tuning to improve performance
   - Apply cross-validation to prevent overfitting

3. **Evaluation & Comparison**
   - Compare models using accuracy, precision, recall, F1-score
   - Visualize results with confusion matrices and ROC curves
   - Select the best model for deployment

## Results
The results of the experiments will be documented in a final report, which includes:
- Performance metrics of each classifier
- Justification for the selected model
- Summary of findings and future improvements

## Dependencies
To install the required libraries, run:
```sh
pip install -r requirements.txt
```

## Submission Requirements
- A well-structured report (max 5 pages) detailing methodology, results, and conclusions.
- Code submission including all scripts and notebooks used.

## Author
Caolán Maguire
