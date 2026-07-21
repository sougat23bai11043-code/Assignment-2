# Assignment-2
# Customer Churn Prediction using Logistic Regression

A Machine Learning project developed as part of **AI-ML Assignment 2**. This project predicts whether a customer is likely to leave (churn) using a **Logistic Regression** model.

---

#  Project Overview

Customer churn prediction helps telecommunication companies identify customers who are likely to discontinue their services. This project uses demographic and service-related information to build a Logistic Regression model for churn prediction.

---

#  Objective

- Predict customer churn using Logistic Regression.
- Perform data preprocessing.
- Handle missing values.
- Encode categorical variables.
- Evaluate the model using classification metrics.
- Visualize results using a Confusion Matrix.

---

#  Dataset

**Dataset Name**

Telco Customer Churn Dataset

**Source**

Kaggle

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

#  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

#  Features Used

The dataset includes customer information such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Contract
- Payment Method
- Monthly Charges
- Total Charges

###  Target Variable

**Churn**

---

#  Methodology

## Step 1: Data Understanding

- Loaded the dataset.
- Displayed the first five records.
- Identified numerical and categorical features.
- Selected the target variable.

---

## Step 2: Data Preprocessing

- Checked for missing values.
- Handled missing values.
- Encoded categorical variables.
- Split the dataset into 80% training and 20% testing data.

---

## Step 3: Model Development

- Built a Logistic Regression model.
- Trained the model using the training dataset.
- Predicted customer churn on the testing dataset.

---

## Step 4: Model Evaluation

The model was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

#  Results

The Logistic Regression model achieved good classification performance. The evaluation metrics and confusion matrix indicate that the model can effectively distinguish between customers who churn and those who remain.

---

#  Key Findings

- Contract type strongly influences customer churn.
- Customers with higher monthly charges are more likely to churn.
- Longer-tenure customers are generally less likely to churn.
- The Logistic Regression model provides a good baseline for churn prediction.

---

#  Conclusion

This project demonstrates the implementation of Logistic Regression for customer churn prediction. After preprocessing the data and training the model, the results showed effective classification performance based on Accuracy, Precision, Recall, F1-Score, and the Confusion Matrix. Features such as contract type, tenure, and monthly charges play an important role in predicting customer churn. One limitation of Logistic Regression is that it assumes a linear relationship between the input features and the log-odds of the target variable, which may not capture complex patterns in customer behavior.

---

#  Repository Structure

```text
Assignment-2/
│
├── Assignment-2.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md
```

---

#  How to Run

1. Clone this repository.

```
git clone https://github.com/your-username/Assignment-2.git
```

2. Install the required libraries.

```
pip install pandas numpy matplotlib scikit-learn
```

3. Open **Assignment-2.ipynb** in Google Colab or Jupyter Notebook.

4. Run all cells.

---

#  Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn

---

#  Author

**Name:** Sougat Das

**Course:** AIML

**Assignment:** Assignment-2

**Topic:** Customer Churn Prediction using Logistic Regression

---

#  Acknowledgement

This project was completed as part of the AI & ML course assignment using the Telco Customer Churn Dataset from Kaggle.
