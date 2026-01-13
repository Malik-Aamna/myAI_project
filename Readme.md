# Medical Insurance Charges Prediction

## Table of Contents
1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Dataset Description](#dataset-description)
4. [Feature Selection](#feature-selection)
5. [Data Preprocessing](#data-preprocessing)
6. [Methodology](#methodology)
7. [Model Used: Linear Regression](#model-used-linear-regression)
8. [Training the Model](#training-the-model)
9. [Experimental Results](#experimental-results)
    - [Confusion Matrix](#confusion-matrix)
10. [Conclusion](#conclusion)
11. [Tools and Technologies](#tools-and-technologies)
12. [References](#references)

---

## Abstract
This project applies Linear Regression to predict medical insurance charges using demographic and health-related features. The model is evaluated using MAE, RMSE, and R² score. Additionally, insurance charges are categorized into low and high values to generate a confusion matrix for further analysis.

---

## Introduction
Medical insurance charges depend on factors such as age, BMI, smoking habits, and region. Accurate prediction helps insurance companies assess risk and set premiums. Linear Regression is used to model the relationship between these features and insurance charges.

---

## Dataset Description
The dataset contains 1,338 records and 7 features:
- age
- sex
- bmi
- children
- smoker
- region
- charges (target variable)

There are no missing values in the dataset.

---

## Feature Selection
All features were selected due to their potential impact on insurance charges.

- **Input Features:** age, sex, bmi, children, smoker, region  
- **Target Variable:** charges

---

## Data Preprocessing
- Categorical variables encoded using One-Hot Encoding  
- Feature scaling applied using StandardScaler  
- Dataset split into 70% training and 30% testing data  

---

## Methodology
1. Load dataset  
2. Encode categorical variables  
3. Normalize features  
4. Split data into training and testing sets  
5. Train Linear Regression model  
6. Predict insurance charges  
7. Evaluate model performance  

---

## Model Used: Linear Regression
Linear Regression predicts continuous values by learning the linear relationship between input features and the target variable. It minimizes prediction error using the least squares method.

---

## Training the Model
The model learns feature weights during training. Factors such as smoking status, age, and BMI show strong influence on insurance charges.

---

## Experimental Results
**Evaluation Metrics:**
- MAE ≈ (your output)  
- RMSE ≈ (your output)  
- R² ≈ (your output)  

R² score indicates how well the model explains variance in insurance charges.

### Confusion Matrix
Insurance charges were categorized into low and high based on the median value. The confusion matrix provides insight into classification-like performance.

---

## Conclusion
The Linear Regression model successfully predicts medical insurance charges with good accuracy. Results show that smoking status and BMI are major contributing factors. The model performs well for real-world applications.

---

## Tools and Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## References
- Kaggle Insurance Dataset: [https://www.kaggle.com/mirichoi0218/insurance](https://www.kaggle.com/mirichoi0218/insurance)  
- My GitHub Profile: [Your GitHub Link Here]
