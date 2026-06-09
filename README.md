# Data Science & Analytics Internship Projects
### DevelopersHub Corporation

This repository contains solutions for the first three advanced internship tasks assigned as part of the Data Science & Analytics Internship Program at DevelopersHub Corporation.

---

# Task 1: Term Deposit Subscription Prediction

## Objective

The objective of this project is to predict whether a bank customer will subscribe to a term deposit after being contacted through a marketing campaign.

## Dataset

Bank Marketing Dataset (UCI Machine Learning Repository)

## Project Workflow

- Data Loading and Exploration
- Data Cleaning and Preprocessing
- Encoding Categorical Features
- Feature Selection
- Model Training
  - Logistic Regression
  - Random Forest Classifier
- Model Evaluation
  - Confusion Matrix
  - Precision
  - Recall
  - F1 Score
  - ROC Curve
- Explainable AI using SHAP
- Business Insights

## Key Visualizations

- Target Distribution
- Correlation Analysis
- ROC Curve
- Feature Importance
- SHAP Summary Plot

## Results

The Random Forest model achieved better predictive performance than Logistic Regression and effectively identified customer characteristics influencing subscription behavior.

## Key Insights

- Call duration strongly impacts subscription probability.
- Customers contacted multiple times showed higher conversion rates.
- Previous campaign outcomes influence customer decisions.

---

# Task 2: Customer Segmentation Using K-Means Clustering

## Objective

The objective of this project is to segment customers into distinct groups based on annual income and spending behavior to support targeted marketing strategies.

## Dataset

Mall Customers Dataset

## Project Workflow

- Data Loading and Exploration
- Exploratory Data Analysis (EDA)
- Data Standardization
- Elbow Method for Optimal Cluster Selection
- K-Means Clustering
- PCA-based Cluster Visualization
- Segment Analysis
- Marketing Strategy Recommendations

## Key Visualizations

- Income Distribution
- Spending Score Distribution
- Elbow Curve
- Customer Segments
- PCA Cluster Visualization

## Results

Five customer segments were identified, each exhibiting different purchasing patterns and spending habits.

## Marketing Strategies

### Cluster 1 – High Income, High Spending

- Premium Membership Programs
- Exclusive Product Launches
- VIP Rewards

### Cluster 2 – High Income, Low Spending

- Personalized Product Recommendations
- Loyalty Campaigns

### Cluster 3 – Low Income, High Spending

- Discount Offers
- Seasonal Promotions

### Cluster 4 – Low Income, Low Spending

- Awareness Campaigns
- Budget-Friendly Products

### Cluster 5 – Average Customers

- Retention Programs
- Cross-Selling Opportunities

## Key Insights

- Income alone does not determine spending behavior.
- Customer segmentation enables more efficient marketing decisions.
- High-spending customers contribute significantly to overall revenue.

---

# Task 3: Energy Consumption Forecasting

## Objective

The objective of this project is to forecast household energy consumption using historical energy usage patterns and compare forecasting approaches.

## Dataset

Appliances Energy Prediction Dataset

## Project Workflow

- Data Loading and Cleaning
- Datetime Conversion
- Time-Series Feature Engineering
- Exploratory Data Analysis
- Forecasting Model Development
  - ARIMA
  - Prophet
  - XGBoost / Random Forest
- Model Evaluation
  - MAE
  - RMSE
- Actual vs Forecast Visualization
- Feature Importance Analysis
- Business Insights

## Key Visualizations

- Energy Consumption Over Time
- Daily Average Consumption
- Actual vs Forecast Comparison
- Feature Importance Chart
- Model Comparison Results

## Results

The forecasting models were evaluated using MAE and RMSE metrics. The best-performing model demonstrated stronger forecasting accuracy and better captured energy consumption patterns.

## Key Insights

- Energy consumption varies across different time periods.
- Weather-related variables impact appliance energy usage.
- Machine learning models captured nonlinear relationships more effectively than traditional forecasting techniques.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Statsmodels
- Prophet
- SHAP
- XGBoost

---

# Repository Structure

Data-Science-Internship-Projects/

├── Task-1-Bank-Marketing/

│   ├── notebook.ipynb

│   ├── README.md

│   ├── requirements.txt

│   └── images/

│

├── Task-2-Customer-Segmentation/

│   ├── notebook.ipynb

│   ├── README.md

│   ├── requirements.txt

│   └── images/

│

├── Task-3-Energy-Forecasting/

│   ├── notebook.ipynb

│   ├── README.md

│   ├── requirements.txt

│   └── images/

│

└── requirements.txt

---

# Dataset Sources

### Task 1 – Bank Marketing Dataset

https://archive.ics.uci.edu/dataset/222/bank+marketing

### Task 2 – Mall Customers Dataset

https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Task 3 – Appliances Energy Prediction Dataset

https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction

---

# Conclusion

These projects demonstrate practical applications of machine learning, customer analytics, and time-series forecasting techniques. The work covers supervised learning, unsupervised learning, model evaluation, explainable AI, forecasting, and business insight generation using real-world datasets.
