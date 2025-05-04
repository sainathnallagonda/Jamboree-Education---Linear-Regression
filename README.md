# Jamboree Education - Linear Regression

## Project Overview
Jamboree Education provides guidance to students aiming for top colleges abroad. This project develops a regression model to predict the probability of graduate admission based on various student attributes.

## Objectives
- **Perform Exploratory Data Analysis (EDA)** to understand feature distributions.
- **Build and evaluate regression models** (Linear Regression, Ridge, and Lasso) to predict admission chances.
- **Check model assumptions** such as multicollinearity, normality, and homoscedasticity.

## Dataset
The dataset contains key predictors influencing graduate admissions:
- **GRE Score**
- **TOEFL Score**
- **University Rating**
- **SOP (Statement of Purpose Score)**
- **LOR (Letter of Recommendation Score)**
- **CGPA**
- **Research Experience**
- **Chance of Admit (Target Variable)**

## Tools and Libraries Used
- **Python** (`pandas`, `numpy`, `seaborn`, `matplotlib`)
- **Machine Learning** (`scikit-learn`, `statsmodels`)
- **Feature Engineering** (`StandardScaler`, `Label Encoding`)
- **Statistical Analysis** (VIF, correlation matrices)

## Methodology
1. **Data Preprocessing**: Cleaning and preparing the dataset, handling missing values, and dropping unnecessary columns.
2. **EDA & Visualization**: Distribution plots, bar charts, pair plots, and correlation heatmaps.
3. **Model Building**:
   - **Linear Regression**: Baseline model.
   - **Ridge Regression**: To reduce multicollinearity.
   - **Lasso Regression**: To perform feature selection.
4. **Model Evaluation**:
   - `R² Score`, `Mean Absolute Error (MAE)`, `Root Mean Squared Error (RMSE)`.
   - Comparison of model predictions with actual values.
5. **Assumptions Validation**:
   - Residual Analysis (`QQ Plot`, `Residual Plot`, `Histogram`).
   - Checking multicollinearity using **Variance Inflation Factor (VIF)**.

## Key Findings
- **CGPA is the most influential feature** in predicting admission chances.
- **High correlation among GRE, TOEFL, and CGPA** impacts prediction accuracy.
- **Ridge Regression performs best**, reducing multicollinearity while retaining predictive power.
- **Lasso Regression weakens performance**, suggesting most features contribute significantly to the outcome.
- **Students with higher University Ratings and Research experience have better chances of admission**.

## Future Improvements
- Adding features such as **extracurricular activities, internships, work experience** to improve model accuracy.
- Creating a **composite score** that combines GRE and TOEFL effects.
- Building an **interactive Tableau dashboard** for better visualization.

## Repository Contents
- `jamboree_linear_regression.ipynb` - Jupyter Notebook with full analysis.
- `Jamboree_Admission.csv` - Dataset file.
- `README.md` - This file.

## Conclusion
This project provides insights into the graduate admission process using **regression models**. By analyzing key features and validating model assumptions, this approach assists students in understanding how different factors impact their admission probabilities.
