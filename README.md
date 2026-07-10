# Logistics_Cost_Analytics

A Machine Learning and Data Analytics project that analyzes logistics delivery data to identify the major factors influencing delivery costs and supports cost optimization through predictive analytics.

---

## Project Overview

This project performs Exploratory Data Analysis (EDA), Feature Engineering, and Machine Learning on an Indian logistics delivery dataset.

The objective is to analyze delivery operations, understand the factors affecting delivery costs, compare multiple regression models, and generate business recommendations for logistics optimization.

---

## Project Objectives

- Analyze logistics delivery data
- Perform data cleaning and preprocessing
- Explore delivery patterns using visualizations
- Engineer useful features for prediction
- Train multiple machine learning models
- Compare model performance
- Identify major delivery cost drivers
- Generate business recommendations

---

## Dataset

**Source:** Kaggle

**Dataset:** Indian Multi-Partner Delivery Logistics Dataset

The dataset contains:

- Delivery Partner
- Package Type
- Vehicle Type
- Delivery Mode
- Region
- Weather Condition
- Distance (km)
- Package Weight (kg)
- Delivery Rating
- Delivery Status
- Delivery Cost

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Data Preprocessing
        │
        ▼
Machine Learning Models
        │
        ▼
Model Evaluation
        │
        ▼
Feature Importance Analysis
        │
        ▼
Business Insights
        │
        ▼
Business Recommendations
```

---

## Machine Learning Models

The following regression models were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Median Prediction Error

---

## Key Findings

- Delivery distance is the strongest factor influencing delivery cost.
- Package weight significantly impacts transportation expenses.
- Delivery mode contributes to logistics cost variations.
- Random Forest achieved the lowest prediction error among the evaluated models.

---

## Business Recommendations

- Optimize long-distance delivery routes.
- Allocate vehicles based on package weight.
- Improve delivery mode selection for cost efficiency.
- Monitor operational performance using historical logistics data.
- Support delivery cost estimation using predictive analytics.

---

## Project Visualizations

The notebook includes the following analyses and visualizations:

- Dataset Overview
- Summary Statistics
- Distribution of Numerical Variables
- Categorical Variables Analysis
- Correlation Heatmap
- Pairplot
- Delivery Performance Analysis
- Partner Performance Analysis
- Model Comparison
- Actual vs Predicted Plot
- Feature Importance Analysis

---

## Repository Structure

```
Logistics_Cost_Analytics/

│── Logistics_Cost_Analytics.ipynb
│── README.md
│── requirements.txt
│── images/
```

---

## Future Scope

- Route Optimization
- Real-Time Cost Prediction
- Weather API Integration
- Fuel Price Analysis
- Interactive Streamlit Dashboard
- Deployment as a Web Application

---

## Author

**Reva Digraskar**

B.Tech, Electronics and Communication Engineering

National Institute of Technology Jamshedpur

GitHub: https://github.com/ugec67
