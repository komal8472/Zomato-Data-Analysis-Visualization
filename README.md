# Zomato-Data-Analysis-Visualization 

## Project Overview

This project focuses on cleaning, preprocessing, analyzing, and predicting restaurant ratings using the Zomato restaurant dataset. The dataset contains restaurant information such as ratings, votes, costs, online ordering, table booking availability, restaurant type, cuisines, and locations.

The project combines Exploratory Data Analysis (EDA) with Machine Learning techniques to discover insights and predict restaurant ratings.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Pickle

---

## Data Preprocessing

The following preprocessing steps were performed:

* Removed unnecessary columns (`url`, `phone`, `dish_liked`)
* Removed duplicate records
* Handled missing values
* Renamed columns for better readability
* Converted cost values into numeric format
* Cleaned rating values by removing `/5`
* Converted categorical variables using factorization encoding
* Prepared data for machine learning models

---

## Exploratory Data Analysis (EDA)

Several visualizations were created to understand restaurant trends:

* Online Order Analysis
* Table Booking Analysis
* Table Booking vs Rating
* City-wise Restaurant Distribution
* City-wise Rating Analysis
* Restaurant Type Distribution
* Restaurant Type vs Rating
* Service Type Analysis
* Service Type vs Rating
* Cost Distribution Analysis
* Location-wise Restaurant Count
* Most Famous Restaurant Chains

---

## Correlation Analysis

A Kendall Correlation Heatmap was generated to identify relationships between different restaurant features and ratings.

---

## Machine Learning Models

The dataset was split into training and testing sets and multiple regression models were trained:

### 1. Linear Regression

Used as a baseline model for rating prediction.

### 2. Random Forest Regressor

Implemented with 500 estimators to improve prediction performance.

### 3. Extra Trees Regressor

Used for enhanced prediction accuracy and final model generation.

---

## Model Deployment Preparation

The final trained model was saved using Pickle:

```python
pickle.dump(ETree, open('model.pkl', 'wb'))
```

This allows the model to be reused for future prediction applications.

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Data Transformation
4. Feature Encoding
5. Exploratory Data Analysis
6. Correlation Analysis
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Saving

---

## Key Insights

* Online ordering significantly influences restaurant engagement.
* Table booking availability impacts restaurant ratings.
* Restaurant type and location play an important role in customer ratings.
* Popular restaurant chains dominate the market across multiple locations.
* Cost and customer votes show relationships with restaurant ratings.

---

## Results

Successfully cleaned and transformed the Zomato dataset, performed detailed exploratory analysis, trained multiple machine learning models, and developed a restaurant rating prediction system.

---

## Author

**Komal Changdev Gaikwad**

B.Sc. Data Science

Python | Machine Learning | Data Analysis | Data Visualization
