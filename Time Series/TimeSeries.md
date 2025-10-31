# 📈 Univariate Time Series Forecasting using ARIMA and SARIMA

## 🧠 Project Objective
The objective of this project is to perform **univariate time series forecasting** using **ARIMA** and **SARIMA** models.  
The goal is to analyze monthly sales data, understand patterns such as trend and seasonality, and predict future values to support better business decision-making.

---

## 🧰 Tools and Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Statsmodels**
- **Jupyter Notebook**

---
## 🧾 Dataset

**Dataset Name**: SeriesReport-202508260039.csv

**Description**: This dataset contains monthly sales data for a furniture store.

**Source**: Advance Monthly Sales for Retail and Food Services, U.S. Census Bureau.

**Main Columns**:

Period → Represents the time period (month and year)

Value → Represents total monthly sales


## ⚙️ Project Workflow

Data Preprocessing

Load and clean the dataset.

Convert the Period column to datetime and set it as the index.

Handle missing values if any.

Exploratory Data Analysis (EDA)

Visualize the time series to detect trend and seasonality.

Decompose the series into trend, seasonal, and residual components.

Model Implementation

Build and compare ARIMA and SARIMA models.

Determine model parameters (p, d, q) using ACF and PACF plots.

Model Evaluation

Evaluate models using metrics like AIC, BIC, and RMSE.

Select the best-performing model.

Forecasting

Predict the next 5 months of sales.

Visualize the forecast along with historical data.

## 📊 Results

The SARIMA model provided better accuracy by capturing seasonality and trend.

The model forecasted sales for the next 5 months, showing a steady upward trend consistent with historical data.

Evaluation metrics confirmed that the SARIMA model had lower error values compared to ARIMA.

## 🔮 Predicted Output

The forecast visualization clearly displays future sales values for 5 months beyond the dataset’s last date.




## 📈 Key Insights

ARIMA is best for stationary series.

SARIMA is better for data with strong seasonal components.

Forecasting sales helps optimize production and inventory planning.

## 👨‍💻 Author

**Pratik Rawade**

📧 Email: [pratikrawade8@gmail.com](#)  
🔗 LinkedIn: [linkedin.com/in/pratik-rawade/](#)
