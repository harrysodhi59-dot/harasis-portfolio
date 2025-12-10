📞 Customer Churn Prediction (Open-Data ML Project – CRISP-DM)
📌 Overview

This project applies the full CRISP–DM machine learning pipeline to an open-source customer churn dataset.
The objective was to build predictive models that help a subscription-based company identify which customers are most likely to churn.

This project mirrors real business challenges similar to my YMCA WIL project, but uses open data to make the work publicly shareable.

🎯 Business Problem

Customer churn directly affects revenue.
A company wants to:

Predict which customers will leave

Understand factors that drive churn

Focus retention strategies on high-risk segments

Machine learning can support these decisions by identifying patterns in customer behaviour.

🔎 CRISP–DM Workflow
1️⃣ Business Understanding

Questions answered:

Who is churning and why?

Which customer groups are at highest risk?

How can predictions support retention strategies?

2️⃣ Data Understanding

Dataset included attributes such as:

Contract type

Tenure

Payment method

Monthly charges

Internet/phone services

Target: Churn (Yes/No)

Initial insights:

Month-to-month contract customers churned more

Short-tenure customers were highly unstable

High monthly charges correlated with churn

3️⃣ Data Preparation

Processing steps:

Handling missing values

Converting TotalCharges to numeric

Encoding categorical features

Scaling numerical variables

Train/test split

This created a clean dataset ready for modeling.

4️⃣ Modeling

We trained and compared multiple machine learning models:

Model	Purpose	Notes
Logistic Regression	Baseline model	Interpretable + fast
Random Forest	Handles complexity	Good performance
XGBoost/LightGBM	Advanced model	Strong results
⭐ Best Model (example: Random Forest / XGBoost)

High accuracy

Strong recall for churners

Good balance for real business use

5️⃣ Evaluation

Metrics used:

Accuracy

Precision, Recall, F1

ROC-AUC

Confusion matrix

Interpretation:

Recall helped detect most churners

AUC showed strong separation between churn/no-churn

Balanced evaluation ensured reliable predictions

6️⃣ Deployment Concept

A simple deployment pipeline could include:

Streamlit front-end form

Model API endpoint (FastAPI)

Input fields for customer attributes

Output: churn probability + recommended actions

This mirrors the deployment approach used in my YMCA WIL project.

📊 Key Insights

Contract type is one of the strongest churn predictors

Lower-tenure customers require onboarding support

High charges + month-to-month contracts lead to revenue instability

These insights support data-driven retention strategies.

🔧 Tools Used

Python

Pandas

scikit-learn

Matplotlib / Seaborn

XGBoost / LightGBM (optional)

👤 My Role

I completed the full pipeline:

Data cleaning and feature engineering

Exploratory analysis

Model training & optimization

Evaluation and interpretation

Documentation and explanation

🧩 Reflection

This project strengthened my understanding of:

CRISP–DM workflow

Model comparison and evaluation

Business-focused ML interpretation

Deployment considerations

It also provided a strong open-data example of predictive modeling for my portfolio.

📌 More projects coming soon…
[⬅ Back to Home](../index.md)

