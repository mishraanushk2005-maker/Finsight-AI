# 📊 FinSight AI

### Intelligent Financial Planning, Forecasting & Analytics Platform

FinSight AI is an end-to-end **Financial Planning and Time-Series Forecasting** project designed to analyze financial performance, compare actual results with budgets, identify business trends and anomalies, and forecast future revenue using machine learning and deep learning.

The project combines **Data Analytics, Time-Series Forecasting, and LSTM Neural Networks** to simulate an enterprise-style financial planning workflow.

> **Note:** The dataset used in this project is synthetically generated for educational and portfolio purposes. It does not represent confidential or proprietary company data.

---

## 🎯 Project Objective

The main objective of FinSight AI is to build an intelligent financial analytics system that can help answer questions such as:

- How is revenue performing over time?
- Are actual revenues meeting the budget?
- Which departments contribute the most revenue?
- How are expenses changing?
- Are there unusual financial patterns or anomalies?
- What will revenue look like over the next 12 months?
- How accurately can an LSTM model forecast future revenue?

---

## 🏗️ Project Workflow

```text
Financial Dataset
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Financial KPI Analysis
       ↓
Time-Series Analysis
       ↓
Trend & Seasonality
       ↓
Stationarity Analysis
       ↓
Baseline Forecasting Models
       ↓
LSTM Deep Learning Model
       ↓
Model Evaluation
       ↓
12-Month Revenue Forecast
       ↓
Business Insights
```

---

## 📂 Dataset

The project uses a synthetic monthly financial dataset covering **2016–2025**.

### Dataset Information

| Feature | Description |
|---|---|
| Time Period | 2016–2025 |
| Frequency | Monthly |
| Companies | 4 |
| Regions | India, USA, UK, Germany |
| Departments | Sales, Technology, Operations, Marketing, HR |
| Records | 2,400 |
| Target | Revenue |

### Important Features

- `date`
- `company`
- `region`
- `department`
- `revenue`
- `expense`
- `marketing_expense`
- `employee_cost`
- `operations_cost`
- `budget_revenue`
- `budget_expense`
- `profit`
- `profit_margin`
- `revenue_variance`
- `revenue_variance_pct`
- `expense_variance`
- `expense_variance_pct`

---

## 📊 Key Analysis

### 1. Financial KPI Analysis

The project analyzes:

- Total Revenue
- Total Expenses
- Total Profit
- Profit Margin
- Revenue Variance
- Expense Variance

### 2. Budget vs Actual Analysis

Actual financial performance is compared against budgeted values to identify:

- Positive revenue variance
- Negative revenue variance
- Expense overruns
- Underperformance

### 3. Trend Analysis

Monthly financial trends are analyzed to identify:

- Long-term revenue growth
- Expense growth
- Profit trends
- Business cycles

### 4. Seasonality Analysis

The project investigates recurring monthly patterns in revenue using:

- Monthly aggregation
- Seasonality visualization
- Seasonal decomposition concepts
- Seasonality heatmaps

### 5. Anomaly Detection

Financial outliers are identified using statistical techniques such as:

- IQR
- Rolling statistics
- Revenue/expense deviation analysis

---

## 🤖 Time-Series Forecasting

Multiple forecasting approaches are compared.

### Baseline Models

The project establishes simple forecasting baselines using:

- Naive Forecast
- Seasonal Naive Forecast
- ARIMA

These models provide a benchmark before applying deep learning.

### LSTM Model

A **Long Short-Term Memory (LSTM)** neural network is used to capture sequential patterns in historical revenue.

```text
Historical Revenue
        ↓
Data Scaling
        ↓
Sliding Window
        ↓
LSTM Layer
        ↓
Dense Layer
        ↓
Predicted Revenue
```

The model is evaluated using:

- MAE — Mean Absolute Error
- RMSE — Root Mean Squared Error

---

## 📈 Visualizations

The project includes interactive and analytical visualizations such as:

- Executive KPI dashboard
- Revenue trend
- Expense trend
- Profit trend
- Actual vs Budget
- Revenue by company
- Department contribution
- Profit margin comparison
- Seasonality heatmap
- Rolling 12-month trend
- Expense outlier analysis
- Revenue variance analysis
- ACF/PACF plots
- LSTM learning curve
- Actual vs predicted revenue
- Future 12-month forecast

---

## 🛠️ Technologies Used

### Programming

- Python

### Data Analysis

- Pandas
- NumPy

### Visualization

- Plotly
- Matplotlib
- Seaborn

### Statistics & Forecasting

- Statsmodels
- ADF Test
- ACF
- PACF
- ARIMA

### Machine Learning

- Scikit-learn

### Deep Learning

- TensorFlow / Keras
- LSTM

### Development

- Jupyter Notebook
- Google Colab
- VS Code
- Git & GitHub

---

## 📁 Project Structure

```text
FinSight-AI/
│
├── data/
│   └── financial_fpa_monthly.csv
│
├── notebooks/
│   └── FinSight_AI_Portfolio_Visualizations.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/mishraanushk2005-maker/Finsight-AI.git
```

### 2. Navigate to the project

```bash
cd Finsight-AI
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn statsmodels tensorflow jupyter
```

### 4. Open the notebook

```bash
jupyter notebook
```

Then open:

```text
notebooks/FinSight_AI_Portfolio_Visualizations.ipynb
```

Alternatively, the notebook can be executed directly in **Google Colab**.

---

## 💡 Business Value

FinSight AI demonstrates how data science can support financial planning and decision-making by:

- Improving revenue forecasting
- Monitoring financial performance
- Identifying budget variances
- Detecting unusual financial behavior
- Understanding seasonal patterns
- Supporting future planning
- Providing data-driven business insights

The project is designed around an **FP&A-style workflow**, where historical financial data is transformed into forecasts and actionable insights.

---

## 🔮 Future Improvements

Potential extensions include:

- Expense forecasting
- Profit forecasting
- Multi-step forecasting for multiple financial KPIs
- Automated anomaly detection
- What-if scenario analysis
- Budget recommendation system
- Streamlit dashboard
- Automated business insight generation using an LLM
- SAP-oriented financial planning integration
- Model deployment using cloud services

---

## 👨‍💻 Author

**Anushk Mishra**

B.Tech Computer Science & Engineering

### Areas of Interest

- Data Science
- Machine Learning
- Deep Learning
- Time-Series Forecasting
- Generative AI
- Business Analytics

---

## ⭐ Project Highlights

```text
✔ End-to-End Data Science Project
✔ Financial Analytics
✔ Time-Series Forecasting
✔ ARIMA Baseline
✔ LSTM Deep Learning
✔ Budget vs Actual Analysis
✔ Anomaly Detection
✔ Business KPI Analysis
✔ 12-Month Revenue Forecast
✔ Interactive Visualizations
```

---

### 📌 Disclaimer

This project is created for **educational and portfolio purposes**. The financial dataset is synthetic and does not represent actual financial information from High Insights or any other organization.
