# 📈 Stock Market Index Analysis & Forecasting

This repository contains advanced analytical and forecasting models applied to the **Dow Jones Industrial Average** index. It includes **statistical analysis**, **outlier detection**, **time series decomposition**, and a **hybrid SARIMA + SVM model** for improved prediction accuracy.

## 🔍 Project Overview

The analysis is performed in two complementary parts:

1. **Statistical & Temporal Analysis**  
   - Segmentation of historical data (before 1980, 1980–2000, 2000 onwards)  
   - Outlier detection using Z-Score  
   - Day, month, and year-based behavior analysis  
   - STL decomposition to extract trend, seasonal, and residual components  
   - Stationarity and normality tests using ADF and KS tests

2. **Forecasting Model: Hybrid SARIMA + SVM**
   - Anomaly detection with Isolation Forest
   - SARIMA modeling of linear trends and seasonality
   - Support Vector Regression (SVM) to predict non-linear residuals
   - Model evaluation via MSE, RMSE, MAE, and diagnostic tests

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `DowJones second edition.py` | Exploratory data analysis, segmentation, statistical summary, and decomposition |
| `Sarima + SVM.py` | Time series forecasting using a hybrid model (SARIMA + SVM) with anomaly handling |
| `D.D.A Analysis on Stock Market index.pdf` | Presentation summarizing digital data analysis and modeling methodology |
| `Statistical Analysis on Stock Market index.pdf` | Presentation focusing on statistical and seasonal analysis across time periods |

## 🧪 Key Techniques Used

- **Z-Score Outlier Detection**
- **STL Decomposition** for trend and seasonality extraction
- **ADF Test** for stationarity check
- **Kolmogorov–Smirnov Test** for normality
- **SARIMA Model** for time series forecasting
- **Support Vector Regression (SVR)** for residual learning
- **Isolation Forest** for anomaly detection
- **Quantile Normalization** for handling distribution skew

## ⚙️ Technologies & Libraries

- Python 3.x
- NumPy, Pandas, Matplotlib, Seaborn
- Statsmodels, Scikit-learn
- SciPy, PyGAD (for GA optimization)
- Jupyter Notebook or any IDE that supports Python

## 📈 Forecasting Model Highlights

- The hybrid model uses **SARIMA** to capture the linear patterns and **SVM** to model the non-linear components in residuals.
- Outliers in returns are handled via interpolation for improved data stability.
- Diagnostic tests confirm **stationarity of residuals** and identify non-normal distributions, justifying hybrid modeling.

## 🧠 Future Work

- Extend anomaly detection using matrix profiles
- Apply LSTM or transformer-based deep learning models
- Deploy the model with live stock index updates for real-time forecasting

## 📎 Citation

If you use this work, please cite:

**Bahare Nasir** – *Stock Market Index Forecasting using SARIMA + SVM Hybrid Models*, 2025.

---

## 📬 Contact

For collaboration, questions or suggestions:  
**Email:** bahare.na@hotmail.com
**LinkedIn:** [linkedin.com/in/baharanasir](https://www.linkedin.com/in/baharanasir)

