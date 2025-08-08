
---

# 💻 Laptop Price Predictor

A GUI-based machine learning application that predicts the price of a laptop based on its specifications using **Linear Regression**. This project was developed as a semester project for the **Probability and Statistics** course.

---

## 📌 Problem Statement

With the increasing variety of laptops and their specifications, consumers often struggle to determine a fair market price. This tool leverages machine learning to estimate laptop prices based on key parameters such as RAM, SSD, processor, graphics card, etc.

---

## 🎯 Objective

To develop an accurate and user-friendly laptop price prediction tool using a **Linear Regression** model. The system helps users make informed buying/selling decisions based on hardware features.

---

## 📊 Dataset

* 📥 Source: [Kaggle - Laptop Prices Dataset](https://www.kaggle.com/datasets/anubhavgoyal10/laptop-prices-dataset)
* 📌 Features:

  * Brand, Processor Details, RAM Size & Type, SSD/HDD Storage
  * OS & OS Bit, Graphics Card Size, Weight Category
  * Touchscreen & MS Office Availability, Warranty
  * 💰 Target Variable: Price

---

## 🧪 Results Summary

* ✔️ **Model:** Linear Regression
* 🔍 **Important Features (via Heatmap):**

  * `weight`, `graphic_card_gb`, `ssd`, `ram_gb`
* 📈 **Evaluation:** R² score for accuracy estimation
* 📊 **Visualizations:**

  * Histograms, Pie Charts, Correlation Heatmap
  * Normal Distribution Fitting
  * Predicted vs Actual Price Scatter Plot
* 🧠 **Insights:** Lightweight and RAM-heavy laptops showed higher correlation with price.

---

## 🖥️ GUI Application

The application is built using **Tkinter** and provides:

* ✅ Dataset Upload and Preview
* ✅ Feature Selection via Dropdowns
* ✅ Visualizations (Pie Charts, Histograms, Heatmaps)
* ✅ Laptop Price Prediction
* ✅ Accuracy Display (R² Score)
* ✅ SweetViz-based HTML Report Generation

---

## 🧠 Technologies Used

* Python
* Tkinter (GUI)
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn (ML)
* SweetViz (EDA)
* SciPy (Normal Distribution)

---


## 📈 Future Work

* Replace Linear Regression with Random Forest or XGBoost for better accuracy
* Add feature selection and outlier handling
* Deploy as a web app using Streamlit or Flask
* Expand dataset to include newer models and brands

---
