# Air Quality Analysis & Forecasting

This project focuses on analyzing air quality data and building predictive models to forecast pollution levels.  
It is divided into milestone-based Jupyter Notebooks.

---

## 📂 Repository Structure

- **Milestone 1**  
  - Loads and inspects raw air quality data (`city_hour.csv`).  
  - Cleans and preprocesses pollutant data (`PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, Xylene`).  
  - Handles missing timestamps and imputes missing values.  
  - Computes AQI (Air Quality Index) using pollutant sub-indices.  
  - Generates **data quality metrics** for completeness and validity.  

- **Milestone 2**  
  - Loads processed dataset (`air_quality_features.csv`).  
  - Implements **time-series forecasting models**:  
    - ARIMA  
    - Prophet  
    - LSTM (RNN)  
  - Evaluates models using **RMSE** and **MAE**.  

---

## ⚙️ Requirements

- Python 3.8+
- Jupyter Notebook / JupyterLab  
- Required libraries:
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
  - statsmodels  
  - prophet  
  - tensorflow / keras  
