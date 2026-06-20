#  Flight Price Prediction using Machine Learning

## Overview

This project develops a machine learning model to predict airline ticket prices based on various flight-related factors such as airline, source city, destination city, departure time, arrival time, number of stops, travel duration, travel class, and days left before departure.

The project demonstrates a complete end-to-end machine learning workflow, including data preprocessing, feature engineering, model training, hyperparameter tuning, and model evaluation.

---

## Business Problem

Flight ticket prices vary significantly depending on several factors, making it difficult for travelers and businesses to estimate costs accurately.

This project aims to:

- Predict flight ticket prices using historical flight data.
- Identify the key factors affecting airfare.
- Demonstrate practical machine learning techniques for regression problems.
- Generate actionable insights from transportation data.

---

## Dataset Information

The dataset contains information about airline flights, including:

| Feature | Description |
|----------|------------|
| Airline | Airline company |
| Source City | Departure city |
| Destination City | Arrival city |
| Departure Time | Flight departure period |
| Arrival Time | Flight arrival period |
| Stops | Number of stops |
| Duration | Total travel duration |
| Class | Economy or Business |
| Days Left | Days remaining before departure |
| Price | Flight ticket price (Target Variable) |

---

## Project Workflow

### 1. Data Cleaning

- Removed unnecessary columns
- Checked for missing values
- Verified data quality

### 2. Exploratory Data Analysis (EDA)

- Analyzed ticket price distributions
- Investigated relationships between features and price
- Visualized trends and patterns

### 3. Feature Engineering

- Converted categorical variables into numerical representations
- Applied encoding techniques
- Prepared data for machine learning algorithms

### 4. Model Building

Implemented:

- Random Forest Regressor

### 5. Hyperparameter Tuning

Optimized model performance using:

- GridSearchCV
- RandomizedSearchCV

### 6. Model Evaluation

Performance measured using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

## Key Skills Demonstrated

### Data Analysis
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis

### Machine Learning
- Regression Modeling
- Random Forest Algorithm
- Hyperparameter Optimization
- Model Evaluation

### Data Preprocessing
- Feature Engineering
- One-Hot Encoding
- Data Transformation

### Programming
- Python
- Pandas
- NumPy
- Scikit-Learn

---

## Results

The Random Forest Regression model successfully learned complex relationships between flight characteristics and ticket prices, enabling accurate price prediction and providing insights into the factors influencing airfare.

Key influential factors include:

- Travel Class
- Airline
- Number of Stops
- Flight Duration
- Booking Timing
- Route Selection

---

## Project Structure

```text
Flight-Price-Prediction/
│
├── flite_details.ipynb
├── dataset.csv
├── README.md
└── requirements.txt
```

## Future Improvements

- Deploy the model using Streamlit
- Build an interactive price prediction dashboard
- Compare performance with XGBoost and Gradient Boosting models
- Integrate real-time flight data APIs

---

## Author

### Thamina Islam Mishu

Aspiring Data Analyst passionate about transforming data into actionable insights through analytics and machine learning.

### Skills

- Python
- SQL
- Excel
- Power BI
- Machine Learning
- Data Analysis

### Connect With Me

- LinkedIn: www.linkedin.com/in/tahmina-islam24
- GitHub: https://github.com/MishuTI

---

## Resume Project Description

Developed a Flight Price Prediction model using Random Forest Regression, performing data cleaning, feature engineering, hyperparameter tuning, and predictive analytics to forecast airline ticket prices with high accuracy.
