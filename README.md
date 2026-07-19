# 📈 Time Series Modeling of Air Quality in Nairobi

## WorldQuant University Applied Data Science Lab

This project explores time series forecasting of PM2.5 air pollution levels in Nairobi, Kenya. The objective is to build and evaluate statistical forecasting models capable of predicting future air quality measurements using historical sensor data.

The project forms part of the WorldQuant University Applied Data Science curriculum and demonstrates practical skills in data wrangling, exploratory data analysis, time series forecasting, and model evaluation.

---

## Project Objectives

- Load PM2.5 air quality data from MongoDB
- Clean and prepare the dataset
- Explore temporal patterns
- Create persistence baseline forecasts
- Build Autoregressive (AR) models
- Build ARMA models
- Compare forecasting performance
- Evaluate models using statistical metrics

---

## Dataset

**Source**

Nairobi Air Quality Dataset

Measurements include:

- PM2.5 concentration
- Timestamp
- Sensor ID
- Sensor type

Only observations from **2024** were used for modeling.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- MongoDB
- PyMongo
- Statsmodels
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

- Load data into MongoDB
- Connect using PyMongo
- Extract the Nairobi collection

---

### 2. Data Wrangling

- Parse timestamps
- Set datetime index
- Sort chronologically
- Handle missing values

---

### 3. Exploratory Data Analysis

- Time series visualization
- Distribution analysis
- Sensor exploration
- Autocorrelation (ACF)
- Partial Autocorrelation (PACF)

---

### 4. Baseline Model

Persistence Forecast

Prediction:

> Tomorrow = Today's PM2.5

Evaluation:

- Mean Absolute Error (MAE)

---

### 5. Autoregressive (AR) Model

Model:

AR(p)

Tasks:

- Determine lag order
- Fit AutoReg model
- Walk-forward validation
- Forecast PM2.5

Evaluation:

- MAE
- RMSE
- R²

---

### 6. ARMA Model

Model:

ARMA(2,1)

Evaluation:

- MAE
- RMSE
- R²

---

## Results

Models were compared against a persistence baseline using:

- Mean Absolute Error
- Root Mean Squared Error
- R² Score

The AR and ARMA models demonstrated improved forecasting performance over the baseline approach.

---

## Repository Structure

```
time-series-air-quality-nairobi/

│
├── notebooks/
│     Nairobi_Time_Series_Modeling.ipynb
│
├── images/
│     timeseries.png
│     acf.png
│     pacf.png
│
├── requirements.txt
│
├── README.md
│
├── LICENSE
│
└── .gitignore
```

---

## Skills Demonstrated

- Time Series Forecasting
- Statistical Modeling
- Feature Engineering
- Forecast Evaluation
- MongoDB
- Data Wrangling
- Python Programming
- Machine Learning Fundamentals

---

## Author

**Luzuko Nzayo**

Mathematics Tutor | Data Science Enthusiast

### 🔗 Connect
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/LNzayo)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/luzuko-nzayo-729735104)

---

## Acknowledgements

This project was completed as part of the

**WorldQuant University**
Applied Data Science Program.
⭐ **Star this repository if you found it useful!**

