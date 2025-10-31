# ⚡ Electric Vehicle Sales Analysis of Indian Market

## 📘 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** of **Electric Vehicle (EV) sales data in India**.  
It aims to analyze EV adoption trends, manufacturer performance, and regional growth patterns using open-source datasets.  
The analysis provides insights into sales penetration, fiscal year trends, and market distribution across different states and vehicle categories.

---

## 🎯 Objective
- To explore and analyze EV sales data across Indian states and manufacturers.  
- To identify high-performing states and top manufacturers in EV adoption.  
- To understand market trends using metrics such as **Penetration Rate** and **Compound Annual Growth Rate (CAGR)**.  
- To visualize EV adoption patterns across time, states, and categories for strategic insights.

---

## 🧰 Tools & Libraries Used
- **Python**  
- **Pandas** – Data manipulation and preprocessing  
- **NumPy** – Numerical computations  
- **Matplotlib** & **Seaborn** – Data visualization and correlation analysis  
- **Plotly Express** – Interactive charts and maps  
- **Jupyter Notebook** – Analysis environment

---

## 🗂️ Dataset Description
The analysis is based on three **open-source CSV files** containing EV sales and date dimension data.

### 1. `electric_vehicle_sales_by_state.csv`
| Column | Description |
|:--|:--|
| `date` | The date on which the data was recorded. Format: DD-MMM-YY (monthly data). |
| `state` | The Indian state where the sales data is recorded. |
| `vehicle_category` | The vehicle type (2-Wheeler or 4-Wheeler). |
| `electric_vehicles_sold` | Number of electric vehicles sold in that state and category on the given date. |
| `total_vehicles_sold` | Total vehicles sold (both EV and non-EV) in that state and category. |

---

### 2. `electric_vehicle_sales_by_makers.csv`
| Column | Description |
|:--|:--|
| `date` | The date of data recording (DD-MMM-YY). |
| `vehicle_category` | Vehicle category (2-Wheeler or 4-Wheeler). |
| `maker` | The manufacturer or brand name. |
| `electric_vehicles_sold` | Number of EVs sold by the maker on the given date. |

---

### 3. `dim_date.csv`
| Column | Description |
|:--|:--|
| `date` | The specific date (DD-MMM-YY). |
| `fiscal_year` | The fiscal year corresponding to the date (April–March cycle). |
| `quarter` | The fiscal quarter (Q1, Q2, Q3, Q4). |

---

## 🧮 Key Metrics

### 🔹 Fiscal Year  
India’s **fiscal year** runs from **April 1 to March 31**, used for financial reporting and analysis.

### 🔹 Penetration Rate  
Represents the percentage of EVs among total vehicles sold.  
Penetration Rate =  (Electric Vehicles Sold / Total Vehicles Sold) * 100  

### 🔹 Compound Annual Growth Rate (CAGR)  
Measures the average annual growth rate over a period longer than one year.  
CAGR = [(Ending Value / Beginning Value) ** 1/n] -1

---
## 📊 Results & Insights

Maharashtra, Karnataka, and Tamil Nadu lead in EV adoption.

EV sales show a significant upward trend from FY 2022 to FY 2024.

2-Wheelers dominate EV sales, driven by affordability and urban mobility.

Penetration rates highlight emerging markets in smaller states.

Computed CAGR indicates strong annual growth momentum in EV sales.



## 🚀 Recommendation

1. Invest in Charging Infrastructure Developmen: Collaborate with government and private partners to set up a robust charging network.
2. Leverage Government Incentives and Policy Support: Utilize the FAME II scheme for subsidies on EVs, fleet electrification, and charging infrastructure.
3. Enhance Battery Technology and Local Manufacturing : Establish local battery manufacturing facilities to reduce costs and reliance on imports.
4. Build Awareness and Collaborate for Ecosystem Development: Conduct awareness campaigns to educate consumers about the benefits of EVs.


## 👨‍💻 Author  
**Pratik Rawade**  
📧 Email: [pratikrawade8@gmail.com](#)  
🔗 LinkedIn: [linkedin.com/in/pratik-rawade/](#)
