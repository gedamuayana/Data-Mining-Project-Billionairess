Project: Analyzing and Visualizing the World's Top Billionaires 2024
1. Objective

Understand patterns in global billionaire distribution.

Identify key factors associated with high net worth.

Build and compare predictive models for billionaire net worth.

2. Introduction

The world’s billionaires hold immense influence over the global economy. This project analyzes a 2024 sample dataset of the world’s richest individuals to explore wealth distribution by country, industry, and source of income, and to predict net worth using machine learning models.
The analysis is conducted using Python in Google Colab, focusing on data exploration, visualization, and regression modeling.

3. Data Preparation

A custom dataset of 20 billionaires was created containing the following attributes:

Rank

Name

Net Worth (in billions USD)

Age

Gender

Country

Industry

Source of Wealth

Data cleaning included:

Handling missing values and duplicates

Ensuring correct data types

Creating new analytical features such as AgeGroup, WealthGroup, and IsSelfMade

4. Exploratory Data Analysis (EDA)

Visualizations were used to gain insights into billionaire demographics and wealth patterns:

Top Countries by billionaire count

Net Worth Distribution across individuals

Industries by Total Wealth

Age vs Net Worth correlation

Wealth Sources (Pie Chart)

Gender Distribution (Pie Chart)

Key Findings:

The United States dominates in both number and total wealth of billionaires.

The Technology industry leads in accumulated net worth.

Self-made billionaires account for the majority of the top 20 list.

Male billionaires significantly outnumber females in this dataset.

5. Feature Engineering & Modeling

Engineered features:

AgeGroup (Young, Middle-aged, Senior)

WealthGroup (Medium, High, Ultra-High)

IsSelfMade (Binary indicator)

Models Built:

Linear Regression

Random Forest Regressor

Both models were trained and evaluated using metrics such as R², RMSE, and MAE.

6. Results Summary
Model	R² Score	RMSE	MAE
Linear Regression	0.93	0.40	0.34
Random Forest	0.78	0.70	0.49

Interpretation:

Linear Regression achieved a higher R² score (0.93), indicating better predictive performance on this small dataset.

Random Forest showed more flexibility but performed less effectively due to limited data size.

7. Insights & Discussion

Top Country: United States

Top Industry: Technology

Most Common Wealth Source: Self-Made

Average Age: Around 60 years

Limitations:

Small dataset (20 records only)

Missing economic indicators like revenue, assets, or company valuation

Future Work:

Use larger datasets from reliable financial sources (e.g., Forbes, Bloomberg)

Apply advanced algorithms (XGBoost, SVR, Neural Networks)

Include time-series analysis for billionaire wealth trends

8. Tools and Libraries Used

Python, Google Colab

pandas, NumPy — data analysis

matplotlib, seaborn — visualization

scikit-learn — machine learning

9. Team Members
Name	ID
Gedamu Ayana	1238
Hayimanot Kinde	0070
Abye Alemayehu	0373
Firehwot Abeje	0345
Biniyam Kebere	0240
10. Repository Structure
Data-Mining-Project-Billionaires/
 ┣ mining1.ipynb
 ┣ README.md
 ┗ datasets/
     ┗ billionaires_2024.csv
