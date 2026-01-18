# 🌫️ Bengaluru Air Quality Index (AQI) Analysis & Prediction using Machine Learning

This project performs complete **data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning modeling** to analyze and predict the **Air Quality Index (AQI)** of Bengaluru city using historical pollution data.

---

## 📌 Project Objectives

- Analyze air pollution trends in Bengaluru  
- Handle missing values and outliers  
- Visualize pollutant behavior over time  
- Engineer clean features for modeling  
- Predict AQI using regression models  
- Evaluate model performance  

---

## 📂 Dataset

- City: Bengaluru  
- Time period: 2015 – 2020  
- Features include:

  - PM2.5, PM10  
  - NO, NO2, NOx  
  - NH3, CO, SO2, O3  
  - Benzene, Toluene, Xylene  
  - AQI and AQI_Bucket  

---

## ⚙️ Data Preprocessing Steps

✔ Removed rows with missing AQI  
✔ Dropped rows with excessive missing pollutant values  
✔ Filled missing pollutant values using **city-wise mean imputation**  
✔ Filled remaining missing values with 0  
✔ Outlier detection using mean ± 2×std  
✔ Feature scaling using **Min-Max normalization**  
✔ Encoded AQI categories using **Ordinal Encoding**

---

## 📊 Exploratory Data Analysis

- Time-series scatter plots of pollutants  
- AQI distribution plots  
- Boxplots by city  
- Correlation heatmap  
- Statistical summaries of pollutants  

---

## 🧪 Feature Engineering

- Date converted to ordinal numeric format  
- Pollutants normalized using MinMaxScaler  
- AQI_Bucket converted to numeric labels  
- Outlier filtering per city  
- Dataset prepared for supervised learning  

---

## 🤖 Machine Learning Models Used

### 1️⃣ Linear Regression
Used to model linear trends of AQI over time.

Metrics:
- Mean Squared Error (MSE)
- R² Score
- Mean Absolute Error (MAE)

---

### 2️⃣ Polynomial Regression (Degree 7)

Used to capture non-linear AQI patterns.

---

### 3️⃣ Ridge Regression (Polynomial Degree 12)

Used to:
- Control overfitting  
- Improve model stability using L2 regularization  

---

## 📈 Model Evaluation Metrics

For each model:

- Mean Squared Error (MSE)  
- R² Score  
- Mean Absolute Error (MAE)

Models were trained using an 80/20 train-test split.

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost (imported)  
- Jupyter Notebook  

---

## 🏁 Key Outcomes

- Successfully cleaned a real-world polluted dataset  
- Visualized multi-year pollution trends  
- Built regression models for AQI forecasting  
- Demonstrated feature engineering and preprocessing pipeline  
- Showed limitations of simple time-based AQI prediction  

---

## 🚀 Future Improvements

- Use multiple pollutants as predictors instead of only date  
- Add classification models for AQI category prediction  
- Include time-series models (ARIMA / LSTM)  
- Train city-comparative models  
- Deploy as a web application  

---

## ⚠️ Disclaimer

This project is for educational and research purposes only.  
Predictions should not be used for medical or governmental decision-making.

---


