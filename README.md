# Logistics Cost Analytics

A Data Analytics and Machine Learning project that analyzes logistics delivery data to identify the major factors affecting delivery costs and provides business insights for cost optimization.

---

## Project Overview

This project performs Exploratory Data Analysis (EDA), Feature Engineering, and Machine Learning on an Indian logistics delivery dataset.

The objective is to understand delivery operations, identify the key drivers of delivery cost, compare multiple regression models, and generate actionable business recommendations.

---

## Objectives

- Analyze logistics delivery data
- Perform data cleaning and preprocessing
- Explore delivery patterns through visualizations
- Engineer features for machine learning
- Train and compare regression models
- Identify key delivery cost drivers
- Generate business insights and recommendations

---

## Dataset

**Source:** Kaggle

**Dataset:** Indian Multi-Partner Delivery Logistics Dataset

The dataset includes:

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
Dataset Collection
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
Business Insights
        │
        ▼
Business Recommendations
```

---

## Machine Learning Models

The following models were trained and evaluated:

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
- Package weight significantly affects transportation expenses.
- Delivery mode contributes to logistics cost variations.
- Random Forest achieved the lowest prediction error among the evaluated models.

---

## Business Recommendations

- Optimize long-distance delivery routes.
- Improve vehicle allocation based on package weight.
- Optimize delivery mode selection.
- Use historical logistics data for delivery cost estimation.
- Support operational planning through predictive analytics.

---

## View the Complete Notebook

The complete notebook, including all visualizations, machine learning models, outputs, and business insights, can be viewed here:

**[Open the Project Notebook](./Logistics_Cost_Analytics.ipynb)**

---

## Repository Structure

```
Logistics_Cost_Analytics/

├── Logistics_Cost_Analytics.ipynb
├── README.md
└── requirements.txt
```

---

## Future Scope

- Route Optimization
- Real-Time Cost Prediction
- Weather API Integration
- Fuel Price Analysis
- Interactive Dashboard Development
- Deployment as a Web Application

---

## Author

**Reva Digraskar**

B.Tech, Electronics and Communication Engineering

National Institute of Technology Jamshedpur

GitHub: https://github.com/ugec67
