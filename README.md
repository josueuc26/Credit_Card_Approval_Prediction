
# Credit Card Approval Prediction Using Logistic Regression

![Credit Card](.\img\credit_card.JPG)

## Project Overview

Commercial banks receive numerous applications for credit cards, many of which are rejected for reasons such as high loan balances, low income levels, or excessive credit inquiries. Manually reviewing these applications is tedious, prone to errors, and time-consuming, making automated models like this one highly valuable.

This project focuses on predicting the approval of credit card applications using a Logistic Regression model. I applied various data preprocessing techniques such as handling missing values, categorical encoding, and feature scaling. The model was optimized using GridSearchCV, achieving an accuracy of 86%. This project highlights my skills in data preprocessing and predictive modeling.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Steps](#key-steps)
- [Results](#results)
- [Conclusions](#conclusions)
- [How to Run](#how-to-run)

## Dataset

The dataset used is a small subset of the Credit Card Approval dataset from the UCI Machine Learning Repository. It contains various features that describe the credit card applications received by a bank.

### Key Steps

1. **Exploratory Data Analysis (EDA):** I analyzed the dataset to understand the relationships between features and the target variable (credit card approval).
2. **Data Preprocessing:**
   - Handled missing values using appropriate imputation techniques.
   - Applied categorical encoding to transform categorical variables into numerical format.
   - Scaled the data to normalize features and improve model performance.
3. **Modeling:**
   - Developed a Logistic Regression model for binary classification.
   - Performed hyperparameter tuning using GridSearchCV to optimize the model.
4. **Evaluation:**
   - The model was evaluated using accuracy as the primary metric, achieving a score of 0.86.

## Results

- The final Logistic Regression model achieved an accuracy of 86%.
- The model was fine-tuned using GridSearchCV to identify the optimal parameters.
- The project demonstrated the effectiveness of logistic regression for binary classification tasks in the financial domain.

## Conclusions

- A logistic regression model was implemented and fine-tuned through GridSearchCV.
- The model achieved an accuracy of 0.86, showcasing its ability to predict credit card approvals based on applicant features.
- The model provides a reliable method for automating the credit card approval process, saving time and reducing errors in decision-making.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/josueuc26/credit_card.git
   cd Predicting_Sales
2. Install the required packages:

    ```python
    pip install -r requirements.txt
3. Run the Jupyter notebook:

    ```bash
    jupyter notebook
4. Load the dataset (make sure to place the data file in the correct folder) and execute the notebook.
