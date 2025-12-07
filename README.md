House Price Prediction Using Linear Regression:

A complete end-to-end Machine Learning project that predicts house prices based on features like rooms, area, bathrooms, age, and location. This project demonstrates data cleaning, EDA, preprocessing, model training, evaluation, and visualization using Python and Scikit-learn.

Project Overview
This project builds a Linear Regression model to estimate house prices using a synthetic dataset (houses.csv). It covers the full ML pipeline—from loading data to final prediction and visualization. This is ideal for beginners and intermediate learners exploring supervised learning techniques.

Tech Stack:
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn

Key Steps in the Project:

1️) Data Loading
Load the dataset using Pandas and inspect structure, datatypes, and missing values.

2️) Exploratory Data Analysis (EDA)
Correlation heatmap
Scatterplots (Rooms vs Price)
Missing value analysis

3️) Data Cleaning & Preprocessing
Impute missing values using median/mode
Remove outliers using the IQR method
Convert categorical feature (Location) using One-Hot Encoding

4️) Train-Test Split
Split the data into training (80%) and testing (20%) sets.

5️) Model Training
Train a Linear Regression model using Scikit-learn.

6️) Model Evaluation
Evaluate performance using:
R² Score
Mean Absolute Error (MAE)

7️) Visualization
Plot a regression line comparing actual vs predicted prices (for the Rooms feature).
