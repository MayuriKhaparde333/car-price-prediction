# 🚗 Car Price Prediction using Machine Learning

A Machine Learning web application that predicts the estimated selling price of a used car based on various car specifications such as brand, year, kilometers driven, fuel type, transmission, owner type, location, engine capacity, mileage, seats, and insurance.

The application is built using Python, Scikit-learn, Pandas, and Streamlit.

---

## 📌 Project Overview

Buying or selling a used car can be challenging because the price depends on multiple factors.

This project uses Machine Learning regression algorithms to estimate the selling price of a car based on its features.

The trained Machine Learning model is integrated with a Streamlit web application where users can enter car details and get an estimated selling price instantly.

---

## 🎯 Objectives

- Predict the selling price of used cars.
- Perform data cleaning and preprocessing.
- Perform feature engineering.
- Handle numerical and categorical features.
- Compare multiple Machine Learning regression models.
- Select the best-performing model.
- Deploy the Machine Learning model using Streamlit.

---

## 📊 Dataset

The dataset contains 1000 car records and the following features:

| Feature | Description |
|---|---|
| Brand | Brand of the car |
| Year | Manufacturing year |
| Km_Driven | Total kilometers driven |
| Fuel_Type | Fuel type of the car |
| Transmission | Manual or Automatic |
| Owner | Owner type |
| Location | City/location of the car |
| Engine_CC | Engine capacity in CC |
| Mileage | Mileage of the car |
| Seats | Number of seats |
| Insurance | Insurance availability |
| Selling_Price | Selling price of the car |

### Target Variable

`Selling_Price`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Streamlit
- Machine Learning
- Regression Algorithms

---

## 🔧 Data Preprocessing

The following preprocessing techniques were used:

- Removed duplicate records
- Cleaned text-based categorical values
- Handled missing values using imputers
- Standardized numerical features
- Encoded categorical features using One-Hot Encoding
- Used Scikit-learn Pipeline
- Used ColumnTransformer for preprocessing

---

## 🧮 Feature Engineering

Two additional features were created:

### Car Age

```python
Car_Age = 2026 - Year
