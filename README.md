# Customer Churn Prediction

Predict customer churn using Machine Learning techniques and identify customers likely to leave a service. This project analyzes customer behavior patterns and compares multiple classification algorithms to improve customer retention strategies.

## Project Overview

Customer churn prediction helps businesses identify customers at risk of leaving and take proactive retention actions. This project uses customer data, preprocessing, exploratory analysis, and machine learning models to classify customers as:

- Churned Customers
- Retained Customers

## Dataset Information

- Total Records: 3150
- Total Features: 14
- Dataset includes:

### Categorical Features
- Complains
- Tariff Plan
- Status
- Churn

### Numerical Features
- Call Failures
- Subscription Length
- Charge Amount
- Frequency of Use
- Frequency of SMS
- Customer Value

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- TensorFlow/Keras

## Data Preprocessing

- Checked missing values
- Data cleaning performed
- Converted categorical variables
- Removed multicollinearity using VIF
- Feature selection
- Train-test splitting

## Exploratory Data Analysis

Performed:

- Correlation Heatmap
- Histograms
- Count Plots
- Violin Plots
- Box Plots
- Pair Plots
- Pie Charts

## Machine Learning Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- AdaBoost
- XGBoost
- Artificial Neural Network (ANN)

## Model Performance

### Before Applying VIF (75-25 Split)

| Model | Accuracy |
|---------|----------|
| Logistic Regression | 83.8% |
| KNN | 82.2% |
| SVM | 82.2% |
| Decision Tree | 92.8% |
| Random Forest | 94.0% |
| AdaBoost | 90.9% |
| XGBoost | **94.9%** |

### After Applying VIF

| Model | Accuracy |
|---------|----------|
| Logistic Regression | 89.6% |
| KNN | 89.5% |
| SVM | 82.2% |
| Decision Tree | 91.8% |
| Random Forest | **92.5%** |
| AdaBoost | 89.5% |
| XGBoost | 92.0% |

## Neural Network Results

Best ANN Performance:

- Train-Test Split: 70-30
- Architecture: 20-16-12-8-1
- Optimizer: Adam
- Epochs: 100
- Accuracy: 91.3%

## Key Findings

- XGBoost achieved the highest accuracy before feature reduction: 94.9%
- Random Forest performed best after removing multicollinearity: 92.5%
- Feature engineering and VIF significantly improved model efficiency
- Customer behavior variables strongly influenced churn prediction

## Future Scope

- Multi-channel customer interaction analysis
- Marketing automation integration
- Retention recommendation system
- Gamification strategies for customer engagement

## Team Members

- Thota Shravya
- Vaishali Vadde
- Syed Danish
- Thadem Pravalika

---

⭐ If you found this project useful, give it a star.
