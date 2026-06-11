🩺 Health Insurance Prediction Model
Business Intelligence & Data Science Project — Predicting Insurance Claim Costs

#@ Project Overview
In the health‑insurance industry, accurately forecasting claim expenses is critical for pricing policies, managing risk, and improving customer retention. This project demonstrates how predictive analytics can help insurers estimate claim amounts based on customer demographics and lifestyle factors.

Using Python, Pandas, and Scikit‑Learn, the model applies Linear Regression, Ridge, and Lasso Regression techniques to predict insurance costs. The workflow reflects a real‑world BI use case — transforming raw data into actionable insights for underwriting and pricing teams.

 #Business Problem
Insurance companies often struggle to balance premium pricing with claim payouts. Manual estimation leads to inefficiencies and inconsistent risk assessment.
Objective: Build a supervised machine‑learning model that predicts how much a client will claim, based on key variables such as age, BMI, smoking status, and region.

# Data Description
Dataset: insurance.csv  
Features:

age — Age of the insured individual

sex — Gender

bmi — Body Mass Index

children — Number of dependents

smoker — Smoking status (yes/no)

region — Residential area

expenses — Historical insurance claim amount (target variable)

⚙️ Methodology
Data Exploration & Cleaning

Checked data types, null values, and unique counts.

Encoded categorical variables (sex, smoker, region).

Split data into training (80%) and testing (20%) sets.

#Model Development

Implemented Linear Regression for baseline prediction.

Applied Ridge and Lasso Regression to handle multicollinearity and prevent overfitting.

Evaluated models using .score() and visualized prediction accuracy.

#Prediction Workflow

Created new customer profiles (age, BMI, smoker status, etc.).

Generated claim predictions using trained models.

Compared model performance — Ridge and Lasso achieved ~0.75 accuracy.

# Key Insights
Model Accuracy: ~75% (R² score) — reliable for preliminary claim estimation.

Business Impact: Enables insurers to automate claim forecasting, reduce manual errors, and improve pricing precision.

Scalability: Framework can be extended to include additional risk factors (medical history, policy type, etc.).

# Tools & Technologies
Python (NumPy, Pandas, Scikit‑Learn, Matplotlib, Seaborn)

Machine Learning Algorithms: Linear, Ridge, and Lasso Regression

Environment: Google Colab / Jupyter Notebook

#Results
Built a predictive model that estimates claim amounts for new customers.

Demonstrated how BI and ML can support data‑driven decision‑making in health‑insurance operations.

Delivered a reproducible workflow suitable for integration into Power BI or enterprise analytics dashboards.

# Example Prediction
Age	Sex	BMI	Children	Smoker	Region	Predicted Claim (₹)
32	Female	25	2	Yes	Southwest	29,472
50	Male	30	3	No	Northwest	11,609


#Business Value
This project demonstrates how predictive analytics can transform traditional insurance operations:

Improve risk scoring and premium optimization.

Enhance customer segmentation and policy personalization.

Support data‑driven compliance and audit reporting.

#Repository Structure
Code
/Health-Insurance-Prediction-Model
│
├── insurance.csv
├── Health_insurance_Prediction_using.ipynb
├── README.md
├── /images (dashboard screenshots)
└── requirements.txt
