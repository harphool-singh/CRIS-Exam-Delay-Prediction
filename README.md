# CRIS-Exam-Delay-Prediction

**Prediction of Examination Delay Time in Freight Rakes (CRIS Internship Project)**

---

## 📌 Project Overview

This project was carried out during my internship at the **Centre for Railway Information Systems (CRIS), Ministry of Railways, Government of India**. The main objective is to **predict the examination delay time (time from rake arrival to exam start)** in freight railway operations using **machine learning models**.

The project leverages **data-driven decision-making** to improve operational efficiency, reduce idle waiting times, and enhance scheduling accuracy for freight rake examinations.

---

## 🔍 Problem Statement

Freight rakes often experience delays between **arrival** and **examination start time**, leading to operational inefficiencies.
The goal of this project is to **develop predictive models** that can estimate these delays in advance and help optimize resource allocation.

---

## 📂 Dataset

* The dataset consists of **3.7 lakh+ records** of freight rake operations.
* Key features include:

  * **Arrival Time**
  * **Exam Start Time**
  * **Departure Time**
  * **BPC Date**
  * **Section, Division, Zone**
  * **Rake Type, Commodity, Loading Point**
  * Various categorical and temporal features derived from datetime columns

---

## ⚙️ Methodology

1. **Data Preprocessing & Cleaning**

   * Handling missing values
   * Datetime feature engineering (hour, day, week, etc.)
   * Encoding categorical variables
   * Outlier detection & removal

2. **Exploratory Data Analysis (EDA)**

   * Distribution of delay times
   * Correlation between features
   * Delay variation with **time of day, section, and rake type**

3. **Model Training**

   * Implemented multiple regression models for comparison
   * Applied log transformation on target variable for better accuracy

4. **Evaluation Metrics**

   * **MAE (Mean Absolute Error)**
   * **RMSE (Root Mean Squared Error)**
   * **R² Score**
   * **±15 Minute Accuracy**

---

## ✅ Model Performance

### XGBoost Regressor (Final Model)

* 📊 **Mean Absolute Error (MAE):** 77.95 minutes
* 📈 **R² Score:** 0.6212

The model demonstrates good predictive capability and provides valuable insights for **railway freight examination delay management**.

---

## 🚀 Future Work

* Integration with real-time freight operation systems for live predictions
* Experimenting with **neural network models** for higher accuracy
* Developing a **dashboard/Streamlit app** for visualization and deployment

---

## 🙌 Acknowledgements

This project was completed under the guidance of the **ADAOR Group, CRIS**.
Special thanks to mentors and team members for their support and collaboration.

---

