# Insurance Cost Prediction using Linear Regression

## Project Overview
This project is a beginner-level Machine Learning project where a **Linear Regression model** is used to predict **insurance charges** based on personal and lifestyle-related features.

The main objective of this project is to understand the **core supervised learning workflow**, including data preparation, model training, prediction, and evaluation.

---

## Dataset
The project uses an **Insurance dataset** containing the following features:

### Input Features
- Age  
- Sex  
- BMI  
- Number of Children  
- Smoker  

### Target Variable
- Charges (Insurance Cost)

Categorical features were converted into numerical format before training the model.

---

## Steps Performed
1. Loaded the dataset using Pandas  
2. Performed basic data exploration and visualization  
3. Separated features (X) and target variable (y)  
4. Converted categorical variables into numerical values  
5. Split the data into training and testing sets (80% / 20%)  
6. Trained a Linear Regression model  
7. Made predictions on test data  
8. Evaluated the model using R² score  
9. Compared training and testing performance to analyze model behavior  

---

## Model Evaluation
- R² score was used to evaluate how well the model predicts insurance charges
- Training and testing R² scores were compared to understand:
  - Underfitting
  - Overfitting
  -Understanding underfitting and overfitting using training and testing R² scores
  - Observing generalization behavior through model evaluation


---

## Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Output
The trained model predicts insurance charges and its performance is evaluated on unseen test data.

---

## Learning Note
This project helped in building a strong foundation in regression models, data splitting,
model evaluation, and understanding model performance.

## Author
Amit Parmar
