# u24079431-Mehluli-Ngwenya-Disease-and-Symptom-Diagnoses-Model
# Disease and Symptom Diagnosis Model

## Overview
This project involves the development of a **machine learning-based diagnosis model** designed to predict diseases based on user-provided symptoms. Leveraging datasets such as SymbiPredict, the model demonstrates high accuracy and robust generalizability, with the potential to aid in medical diagnosis and decision-making processes.

The project explores various stages of the machine learning lifecycle, from data preprocessing to model evaluation and deployment. The final model is implemented using logistic regression and fine-tuned with hyperparameter optimization to achieve high accuracy.

## Features
- Predicts diseases based on user-inputted symptoms.
- Built with logistic regression, offering simplicity and explainability.
- Trained on a well-balanced dataset (SymbiPredict) with over 100 disease classes.
- Supports encoded symptom inputs and uses binary feature engineering for representation.
- Provides a user-friendly script to interact with the model.

## Project Structure
- **Dataset**: SymbiPredict dataset (preprocessed and split into training and testing sets).
- **Model**: Logistic Regression model, trained and serialized using `joblib`.
- **Notebooks**:
  - `(u24079431) Disease and Symptom Diagnoses model.ipynb`: Exploratory Data Analysis, training pipeline, and performance evaluation.
- **Saved Model**: The trained logistic regression model, stored as `logistic_regression_model.joblib`.

## Prerequisites
- Python 3.8+
- Required Python libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `joblib`

Install the libraries using:
```bash
pip install -r requirements.txt
```

## Setup
1. **Clone the repository**:
   ```bash
   git clone : https://github.com/Hluks7/u24079431-Mehluli-Ngwenya-Disease-and-Symptom-Diagnoses-Model.git
   
   ```

2. **Run the model**:
   To make a prediction, run the following:
   ```bash
   python 'logistic_regression_model.joblib'
   ```

3. **User Input**:
   Enter symptoms as a list (e.g., `['fever', 'cough']`), and the script will return the predicted disease.


   

## Usage
### Example Prediction
1. Input:
   ```python
   user_symptoms = ['cough', 'fever', 'headache']
   ```
2. Output:
   ```
   Predicted Disease: Influenza
   ```

## Results
### Performance Metrics:
- **Accuracy**: 100% (on balanced SymbiPredict dataset).
- **F1-Score**: 1.00
- **Precision and Recall**: 1.00

### Visualizations:
![Training and Test Set Class Distributions](Data_Distribution.png)

The above figure illustrates a balanced class distribution, ensuring the model generalizes well across various diseases.


## Contribution
To contribute to this project:
1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request.

## Acknowledgements
This project utilized the SymbiPredict dataset and was developed as part of a machine learning diagnostic system coursework for COS781.

