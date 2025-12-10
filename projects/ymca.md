🏋️‍♂️ YMCA Northern Alberta – Membership Hold Behaviour & Revenue Impact (WIL Industry Project)
📌 Overview

This project was completed as part of my Work-Integrated Learning (WIL) experience with YMCA Northern Alberta.
The goal was to understand how membership hold behaviour impacts overall revenue, and to support management with data-driven insights and predictive models.

🎯 Business Problem

Members often place their accounts “on hold,” which temporarily stops payments.
YMCA wanted to understand:

Which members are most likely to go on hold

What patterns exist across branches, membership types, and time periods

How hold behaviour influences monthly revenue

What operational decisions could reduce unnecessary holds

This reflects a real client problem involving revenue planning and customer retention.

🧹 Data Preparation

After cleaning and engineering the dataset, we created:

A model-ready dataset combining membership, holds, and timeline info

Encoded features (membership type, plus vs non-plus, branch, etc.)

Target variable: Hold = Yes/No

Aggregated revenue metrics to evaluate financial impact

📊 Exploratory Data Analysis (EDA)

Some insights included:

Plus members showed different hold patterns compared to non-plus

Certain branches had higher hold rates

Revenue dips were aligned with spikes in hold activity

Several seasonal patterns appeared in the data

Visuals included:

Hold distribution

Holds by membership type

Revenue trend lines

Branch comparisons

🤖 Machine Learning Models

We tested multiple ML algorithms:

Model	Purpose	Notes
Logistic Regression	Baseline classifier	Fast, interpretable
Random Forest	Non-linear relationships	Good baseline accuracy
LightGBM (Final Model)	Best performance	Handles categorical & imbalanced data well
⭐ LightGBM delivered the strongest results:

High accuracy

Strong recall for predicting members likely to go on hold

Clear feature importance insights

Key features included membership type, tenure, billing cycle, and plus status.

🧠 Explainable AI (XAI)

We generated SHAP explanations to show:

Which features most influenced predictions

Why certain members were classified as high hold-risk

How operational factors impacted model behavior

This made the model transparent and easier for YMCA leadership to trust.

💰 Revenue Impact Insights

Using combined ML + financial analysis:

Hold behaviour was linked to consistent declines in monthly revenue

Certain member segments produced larger revenue drops when on hold

Insights supported strategies to reduce unnecessary holds

📈 Dashboards & Deployment
Power BI Dashboard

Included:

Hold rate by branch

Hold trends

Membership type breakdown

Revenue impact visualizations

Streamlit ML App

Built to allow YMCA staff to:

Input member attributes

Predict hold likelihood

View risk category

Understand decision factors via visuals

🏆 Results & Value Delivered

Delivered actionable insights to the YMCA team

Built interpretable ML models for planning

Provided dashboards + an interactive prediction tool

Supported data-driven decision-making

👤 My Role

I contributed to:

Data cleaning and preparation

EDA visualizations

Model building and evaluation

SHAP model explainability

Streamlit app development

Dashboard creation

Final client-style presentation

🧩 Reflection

This project strengthened my skills in:

Real-world ML workflow

Working with messy industry data

Client communication

Model explainability

Combining ML with business insights

It was a highly valuable industry experience.

📌 More projects coming soon…
