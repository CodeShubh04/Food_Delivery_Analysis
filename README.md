# 🍔 Food Delivery Analysis

## 📌 Project Overview

This project presents a detailed **spatial, temporal, and spatio-temporal analysis** of food delivery data. It involves understanding customer order patterns, delivery performance, and predicting delivery time using advanced geostatistical and machine learning techniques.

---

## 🎯 Objectives

* Analyze **temporal trends** in order frequency
* Identify **spatial delivery patterns** by location
* Use **machine learning** to predict delivery time
* Apply **Kriging** and **Moran's I** for spatial statistics
* Visualize **spatio-temporal dynamics** of food orders

---

## 🗂️ Project Structure

```
📁 Food Delivery Analysis/
│
├── Analysis.ipynb           # Main notebook with full analysis
├── Orders.xlsx              # Customer order data
├── Restaurants.xlsx         # Restaurant location and metadata
├── train.csv                # Training data for delivery time prediction
├── test.csv                 # Test data for evaluation
└── README.md                # Project documentation
```

---

## 📦 Dataset Descriptions

* **Orders.xlsx** – Order-level details like timestamp, delivery time, customer zone, etc.
* **Restaurants.xlsx** – Geographic locations and metadata for all restaurants
* **train.csv** – Structured dataset used to train a delivery time prediction model
* **test.csv** – Dataset to test the model's performance on unseen data

---

## 🔍 Key Analysis

### ⏳ Temporal Analysis

* Daily and weekly order patterns
* Moving averages and seasonality detection
* Decomposition of time series (trend/seasonality/residual)
* Forecasting future orders using ARIMA

### 🌍 Spatial Analysis

* Heatmaps and interactive maps of delivery zones
* Order density and delay by restaurant zone
* Ordinary Kriging to predict delivery time in unknown areas
* Moran’s I to measure spatial autocorrelation

### 🧠 Machine Learning

* Predictive modeling using `train.csv` and `test.csv`
* Feature engineering from spatial and temporal inputs
* Regression modeling for delivery time

### 🗺️ Spatio-Temporal Analysis

* Animated maps of order trends over time
* Zonal delivery delays mapped geographically
* Interactive time-synced visuals using Plotly and Mapbox

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * Data Analysis: `pandas`, `numpy`
  * Visualization: `matplotlib`, `seaborn`, `plotly`
  * Geospatial: `pykrige`, `pysal`, `splot`, `geopandas`
  * Machine Learning: `scikit-learn`
  * Time Series: `statsmodels`, `ARIMA`

---

## 💡 How to Use

1. Clone or download the project folder
2. Install all dependencies:

```bash
pip install pandas matplotlib seaborn plotly pykrige pysal splot statsmodels scikit-learn geopandas
```

3. Place all data files (`Orders.xlsx`, `Restaurants.xlsx`, `train.csv`, `test.csv`) in the same directory
4. Open `Analysis.ipynb` in Jupyter Notebook or JupyterLab
5. Run all cells for a full walkthrough of the project

---

## 📈 Visual Outputs

* Line charts of order trends
* Forecast plots for future demand
* Interactive heatmaps of delivery zones
* Choropleth and Kriging maps
* Animated spatial maps with temporal layers

---
