# 🚲 Bike Rental Demand Prediction

## 📌 Project Overview

Bike Rental Demand Prediction is a Machine Learning project developed to predict the number of bike rentals based on different environmental, weather, and time-related factors.

The project demonstrates the complete Machine Learning workflow, from data exploration and preprocessing to model training, evaluation, and prediction through a user-friendly desktop application.

## 🎯 Problem Statement

Bike rental demand changes according to factors such as time, weather, temperature, humidity, season, and working days.

Accurately predicting rental demand can help bike rental businesses:

* Plan bike availability
* Improve resource management
* Reduce unused bikes
* Prepare for high-demand periods
* Improve customer service

## 📊 Dataset

The project uses the **UCI Bike Sharing Dataset**, specifically the `hour.csv` dataset.

The dataset contains hourly bike rental information along with weather and time-related features.

### Key Features

* Hour
* Season
* Year
* Month
* Holiday
* Weekday
* Working Day
* Weather Situation
* Temperature
* Feeling Temperature
* Humidity
* Windspeed

### Target Variable

**`cnt`** — Total number of bike rentals.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook
* Tkinter

## 🔍 Project Workflow

### 1. Data Collection

Collected and explored the UCI Bike Sharing Dataset.

### 2. Data Preprocessing

* Checked missing values
* Checked duplicate records
* Converted date information
* Created useful date-related features
* Prepared features and target variable

### 3. Exploratory Data Analysis

Analyzed how bike rental demand changes according to:

* Hour of the day
* Weather conditions
* Season
* Day of the week

Visualizations were created using Matplotlib.

### 4. Machine Learning Model

A **Linear Regression** model was implemented to predict bike rental demand.

The dataset was divided into:

* 80% Training Data
* 20% Testing Data

### 5. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

An Actual vs Predicted visualization was also created to analyze model performance.

## 🖥️ Prediction Application

A Tkinter-based desktop application was developed to allow users to enter different conditions such as:

* Season
* Weather
* Hour
* Temperature
* Humidity

The application then provides the predicted bike rental demand.

## 📸 Project Screenshots

Screenshots of the following project stages are included in the `screenshots` folder:

* Dataset exploration
* Data preprocessing
* Exploratory data analysis
* Model training
* Model evaluation
* Prediction application
* Prediction results

## 📈 Results

The project successfully demonstrates an end-to-end Machine Learning workflow for predicting bike rental demand using Linear Regression.

The prediction interface allows users to test different weather and time scenarios and observe the estimated rental demand.

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Data analysis and preprocessing
* Exploratory data analysis
* Data visualization
* Regression modeling
* Model evaluation
* Building a prediction interface
* Presenting and documenting a Machine Learning project

## 👩‍💻 Author

**Saba Noor**

BS Information & Engineering Technology
Superior University

---

⭐ This project was developed as part of a Machine Learning practical project to demonstrate the complete process of building and presenting a predictive model.
