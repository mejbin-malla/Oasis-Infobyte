# Machine Learning Projects Collection

This repository contains three beginner-friendly machine learning and data science projects built using Python.  
The projects focus on classification, regression, and data analysis using real-world datasets.

## Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- KaggleHub  
- Google Colab / Jupyter Notebook  

---

# Project 1: Iris Flower Classification

## Overview

The Iris flower dataset is one of the most popular datasets in machine learning for classification tasks.

The goal of this project is to train a machine learning model that can identify the species of an iris flower based on its measurements.

The model classifies flowers into three species:

- Iris Setosa  
- Iris Versicolor  
- Iris Virginica  

Based on four features:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

## Objective

To build a classification model that predicts the species of an iris flower using given flower measurements.

## Machine Learning Type

Supervised Learning → Classification

## Algorithm Used

- Random Forest Classifier

## Workflow

Dataset Collection  
↓  
Data Preprocessing  
↓  
Train Test Split  
↓  
Model Training  
↓  
Prediction  
↓  
Accuracy Evaluation  

## Expected Output

The model predicts flower species with very high accuracy, generally above 95%.

---

# Project 2: Unemployment Analysis in India

## Overview

Unemployment rate represents the percentage of people who are unemployed out of the total labour force.

During the COVID-19 pandemic, unemployment rates increased sharply in many regions.

This project focuses on analyzing unemployment trends in India using data science techniques.

## Objective

To analyze unemployment patterns across Indian states and understand the impact of COVID-19 on employment.

## Machine Learning Type

Data Analysis / Exploratory Data Analysis (EDA)

## Dataset Information

The dataset includes:

- Region / State  
- Date  
- Estimated Unemployment Rate (%)  
- Estimated Employed  
- Labour Participation Rate (%)  
- Urban / Rural Area  

## Analysis Performed

- Missing Value Detection  
- Statistical Summary  
- State-wise Unemployment Analysis  
- Urban vs Rural Comparison  
- Monthly Trend Analysis  
- Correlation Analysis  

## Visualization Used

- Bar Chart  
- Line Chart  
- Pie Chart  

## Workflow

Download Dataset  
↓  
Load Data  
↓  
Clean Data  
↓  
Analyze State-wise Unemployment  
↓  
Visualize Trends  
↓  
Find Insights  
↓  
 Conclusion  

## Expected Output

The project helps understand employment trends and economic impact during crisis periods.

---

# Project 3: Car Price Prediction

## Overview

Car prices depend on multiple factors such as brand reputation, engine power, mileage, fuel type, age, and many other specifications.

This project uses machine learning to predict the price of a used car based on these features.

## Objective

To build a machine learning model that predicts used car prices using historical car data.

## Machine Learning Type

Supervised Learning → Regression

## Features Affecting Price

- Car Brand  
- Fuel Type  
- Mileage  
- Horsepower  
- Transmission Type  
- Manufacturing Year  
- Kilometers Driven  

## Algorithm Used

- Random Forest Regressor

## Workflow

Download Dataset  
↓  
Load Dataset  
↓  
 Handle Missing Values  
↓  
 Encode Categorical Data  
↓  
 Train Test Split  
↓  
 Train Regression Model  
↓  
 Predict Car Prices  
↓  
 Evaluate Model Performance  

## Evaluation Metrics

- Mean Absolute Error (MAE)  
- R² Score  

## Visualization Used

- Feature Importance Graph  
- Actual vs Predicted Price Scatter Plot  

## Expected Output

The trained model predicts car prices with good accuracy based on multiple car features.

---

# Repository Structure

```
Machine-Learning-Projects/
│
├── Iris_Flower_Classification.ipynb
├── Unemployment_Analysis.ipynb
├── Car_Price_Prediction.ipynb
│
├── datasets/
│
└── README.md
```

---

# Learning Outcomes

Through these projects I learned:

- Data preprocessing techniques  
- Machine learning model training  
- Classification algorithms  
- Regression algorithms  
- Exploratory Data Analysis  
- Data visualization  
- Performance evaluation using metrics  

---

# Future Improvements

- Deploy models using Streamlit  
- Create web application interface  
- Improve accuracy using advanced models  
- Add more datasets and feature engineering  

---

# Author

Created as part of machine learning practice and project learning journey using Python.
