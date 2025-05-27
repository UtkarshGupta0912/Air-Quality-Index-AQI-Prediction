# 🌫️ AQI Prediction and Visualization (Indian Cities)

This project analyzes and predicts **Air Quality Index (AQI)** for Indian cities using environmental features. It includes steps for data extraction, cleaning, visualization, and machine learning modeling using **Random Forest Regression**.

---

## 📁 Dataset

The dataset used is sourced from the **Central Pollution Control Board (CPCB)** via Kaggle and contains:

- `city_day.csv`: Daily pollution data with AQI and pollutant levels for major Indian cities.

You should upload a ZIP file (e.g., `archive.zip`) containing `city_day.csv` to Google Colab or your local environment.

---

## 🔍 Project Highlights

- 📦 Upload and extract dataset from ZIP
- 📊 Time-series AQI trend analysis for Delhi
- 🔥 Correlation heatmap for pollutants
- 🧠 Random Forest Regression to predict AQI
- 📈 Feature importance visualization

---

## 🧠 Features Used for Prediction

The model uses the following features:
- `PM2.5`, `PM10`, `NO`, `NO2`, `NOx`, `NH3`,  
  `CO`, `SO2`, `O3`, `Benzene`, `Toluene`, `Xylene`

---

## 🛠️ Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest)

---

## 🚀 How to Run

### Google Colab Instructions

1. Upload the ZIP file (`archive.zip`) containing `city_day.csv`:
   ```python
   from google.colab import files
   uploaded = files.upload()
