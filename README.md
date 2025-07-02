📈 Overview
This project focuses on predicting customer purchase amounts during Black Friday sales using regression models. By analyzing over 550,000 retail transactions, it demonstrates how machine learning can uncover purchasing patterns and forecast revenue in large-scale datasets.

🎯 Problem Statement
Objective:
Develop predictive models to estimate the purchase amount a customer will spend during Black Friday sales based on their demographics and purchase behavior.

Why It Matters:
Accurate predictions can help retailers:

Personalize marketing campaigns.

Optimize inventory management.

Improve revenue forecasting.

Enhance customer engagement strategies.

🗂️ Dataset Information
Source: Kaggle - Black Friday Sales Prediction

Rows: 550,069

Columns: 12

Target Variable: Purchase (Purchase amount)

Features:

Column Name	Description
User_ID	Unique customer identifier
Product_ID	Unique product identifier
Gender	Sex of customer
Age	Age segment of customer
Occupation	Occupation code of customer
City_Category	Category of city (A/B/C)
Stay_In_Current_City_Years	Number of years in current city
Marital_Status	Marital status
Product_Category_1	Primary product category
Product_Category_2	Secondary product category
Product_Category_3	Tertiary product category
Purchase	Purchase amount (target variable)

🧰 Libraries Used
pandas

matplotlib

seaborn

scikit-learn

🛠️ Algorithms Applied
Linear Regression

Decision Tree Regressor

Random Forest Regressor

Extra Trees Regressor

Each model was evaluated for accuracy and interpretability.

🔍 Exploratory Data Analysis
Analyzed feature distributions and correlations.

Visualized purchase patterns by:

Age group

Gender

Product categories

City category

Handled missing values in product category columns.

✨ Future Work
Hyperparameter tuning to improve model performance.

Testing additional regression algorithms (e.g., Gradient Boosting).

Creating new derived features (e.g., total products purchased).

Normalization and scaling of features.

