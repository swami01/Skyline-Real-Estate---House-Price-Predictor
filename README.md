# 🏠 Skyline Real Estate — House Price Predictor  

![House Price Prediction Banner](assets/banner.png)  

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)  
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression%20Models-orange)]()  
[![Streamlit](https://img.shields.io/badge/Streamlit-App%20Interface-red)](https://streamlit.io/)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)  

---

## 📌 Overview  
This project dives into the **Skyline Real Estate** domain with the goal of building a **highly accurate house price predictor**.  
We analyze **multiple property, neighborhood, and market factors** to help buyers and sellers make informed decisions.  

💡 Our approach goes **beyond just square footage and location**, covering multiple variables to get a realistic price estimate.  

---

## 📊 Features Considered  

| Category | Features |
|----------|----------|
| 🏘 **Neighborhood** | Distance to public transportation, school proximity, crime rates, nearby amenities |
| 🏡 **Property** | Age, renovations, lot size, architectural style, bedrooms, square footage |
| 📈 **Market Trends** | Recent sales data, average income, mortgage rates, economic indicators |

---

## 🎯 Project Objective  
By combining **machine learning algorithms** with **rich datasets**, we aim to:  
- Help **buyers** choose the right property at a fair price  
- Enable **sellers** to price their property competitively  
- Offer **insights** into the factors that drive property values  

---

## 🧠 Machine Learning Approach  

### 🔍 Workflow Diagram  
```mermaid
flowchart TD
    A[Data Collection] --> B[Data Cleaning & Preprocessing]
    B --> C[Feature Engineering]
    C --> D[Model Training: Linear, Decision Tree, Random Forest]
    D --> E[Model Evaluation: MAE, MSE, RMSE, MAPE, R²]
    E --> F[Best Model Selection: Random Forest]
    F --> G[Streamlit Web App Deployment]
