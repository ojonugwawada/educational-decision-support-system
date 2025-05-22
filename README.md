# 📘 Development of Python Software to Address a Supervised Learning Challenge

This project implements a supervised regression model using Python to predict a continuous target variable (`y`) based on 13 numerical features (`x1` to `x13`). It evaluates two machine learning models and provides deep insights using visualization and performance metrics.

## 🎯 Project Objective
To predict target outcomes from structured input data using regression, while evaluating model accuracy, cross-validation reliability, and feature importance.

## 🌾 Relevance to AgriTech
This predictive approach can be adapted for:
- Crop yield forecasting
- Resource efficiency predictions
- Monitoring agronomic metrics over time using regression

## 🧰 Tools & Technologies
- Python (Pandas, NumPy, Plotly, Seaborn)
- Machine Learning: Linear Regression, Random Forest Regressor
- Evaluation: MAE, MSE, RMSE, R², Cross-validation
- Visualization: Correlation heatmaps, histograms, lollipop charts

## 🗂️ Files Included
- `The development of Python software to address a supervised learning challenge (1).ipynb`: Jupyter notebook containing the full code
- `The development of Python software to address a supervised learning challenge.pdf`: Comprehensive project report

## 🔍 Analysis Workflow
1. **Data Loading & Exploration** – Summary stats, histograms, missing value checks
2. **Correlation Analysis** – Heatmap to visualize feature-target relationships
3. **Model Development**
   - Linear Regression
   - Random Forest Regressor
4. **Evaluation Metrics**
   - MAE, MSE, RMSE, R² Score
5. **Cross-Validation** – 5-fold R² scores for model generalizability
6. **Feature Importance**
   - Random Forest: based on importance scores
   - Linear Regression: based on coefficient weights

## 📊 Key Insights
- **Linear Regression** outperformed Random Forest with R² = 0.8821
- Feature `x2` had the strongest predictive influence
- Cross-validation confirmed model consistency with minimal variance

## 🤝 Contribution
This model showcases the ability to build clean, reliable regression systems in Python for applications ranging from academic exercises to real-world predictive analytics in AgriTech, education, and sustainability sectors.
