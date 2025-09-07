# 🌧️ Rainfall Prediction Project

## 📌 Overview
This project predicts **precipitation levels** using the Austin Weather dataset.  
Weather features like **temperature, humidity, dew point, visibility, and wind speed** are used to model rainfall with **Linear Regression**.

---

## ⚙️ Steps
1. **Data Cleaning** – handled missing values, removed irrelevant columns, converted data to numeric.  
2. **Feature Selection** – selected key weather attributes.  
3. **Modeling** – trained and tested Linear Regression.  
4. **Evaluation** – calculated MSE and R² score.  
5. **Visualization** – heatmap, precipitation trends, and scatter plots.  

---

## 📊 Results
- Model performance (R²): *insert your score*  
- Key Insight: **Humidity and dew point** strongly influence rainfall.  

---

## 🚀 Run Locally
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Rainfall_Prediction.ipynb
