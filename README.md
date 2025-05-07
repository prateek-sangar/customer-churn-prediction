# Customer Churn Prediction

Hi, I'm Prateek Sangar. This is a machine learning project where I developed a churn prediction model for a telecom company. The goal was to identify which customers are most likely to stop using the service, using real-world customer data and a logistic regression model.

Working on this project gave me practical experience in applying machine learning to solve real business problems, particularly those related to customer retention and strategic decision-making.

---

## Problem Statement

Customer churn is a major challenge for telecom companies and can significantly affect long-term growth. The objectives of this project were to:
- Understand the patterns and behaviors that lead to customer churn
- Build a predictive model using logistic regression
- Generate actionable insights to help reduce churn

---

## Dataset

The dataset used is publicly available on Kaggle: [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). It includes a variety of features such as:
- Customer demographics
- Services they signed up for (e.g., internet, streaming)
- Account information (e.g., tenure, charges, contract type)
- The target variable: `Churn` (Yes/No)

---

## Tools and Libraries

- Python
- Pandas for data cleaning and manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for machine learning modeling
- Google Colab for development and execution

---

## Exploratory Data Analysis (EDA)

Key findings from EDA:
- Customers on month-to-month contracts are more likely to churn
- Those using electronic payment methods also showed higher churn rates
- Senior citizens and customers who don’t use tech support were more likely to leave
- High total charges combined with short tenure also correlated with churn

These insights were visualized using bar plots, histograms, and correlation heatmaps.

---

## Model Building

- Preprocessing included handling missing values, one-hot encoding categorical features, and dropping irrelevant columns
- The model used was Logistic Regression
- The dataset was split into training and testing sets using a 70-30 ratio

Model performance:
- Test accuracy: 82.4%
- F1-score for the churn class: 0.64

This balance between precision and recall is important for real-world applications where predicting churn incorrectly can have significant business consequences.

---

## Business Insights

- Customers with high monthly charges and short tenure are at a greater risk of leaving
- Month-to-month users are less loyal and should be targeted with loyalty or bundling offers
- Providing tech support and better engagement with senior customers could help retention

---

## What I Learned

Through this project, I gained hands-on experience with:
- The full machine learning workflow: from data loading to model evaluation
- Drawing business-level insights from model outputs
- Understanding the trade-offs in classification problems like churn prediction

---

## How to Run

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
2. Open the `Churn_Prediction.ipynb` notebook in Google Colab or any Jupyter Notebook environment
3. Follow the cells step-by-step
4. Feel free to tweak the model or add your own improvements

---

## About Me

I'm Prateek Sangar, someone who is passionate about using data to solve meaningful problems. My background includes social media marketing and analytics, and I’m now expanding into machine learning and data science. This project reflects my journey into using data not just for reporting, but for making predictive and strategic decisions.

You can connect with me on [LinkedIn](https://www.linkedin.com/in/prateeksangar).
