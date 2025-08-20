# Sales Dashboard & Forecasting

This project analyzes monthly sales data, visualizes trends, and predicts future revenue using a **Linear Regression model**. The goal is to demonstrate how Python and data visualization tools can be combined to provide actionable business insights.

---

## Project Overview

- Load and clean sales transaction data
- Aggregate sales by **month**
- Visualize sales trends with line charts
- Build a **regression model** to forecast next month's revenue
- Provide performance metrics (RMSE, R²) to evaluate the model
- Plot forecasted vs. actual sales for interpretability

---

## Dataset

The project uses the **Superstore Sales Dataset** available on Kaggle:

- [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

**Key Fields Used:**

- `Order Date` → to extract time-based trends
- `Sales` → revenue used as target variable

---

## Tools & Technologies

- **Python**: Data preprocessing, regression modeling
- **Pandas & NumPy**: Data manipulation
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Linear Regression model, evaluation metrics

---

## Methodology

### 1. Data Preprocessing

- Parsed `Order Date` as a datetime object
- Created a new `Month` column for grouping
- Aggregated sales revenue per month

### 2. Data Visualization

- Visualized monthly sales trends using **line plots**
- Highlighted seasonality and fluctuations in revenue

### 3. Regression Modeling

- Converted months into numeric values (`Month_Num`)
- Trained a **Linear Regression model** on historical sales
- Forecasted sales for the next month

### 4. Model Evaluation

- **RMSE (Root Mean Squared Error):** Measures accuracy of predictions
- **R² (R-squared):** Measures how well the model explains the variance in sales

---

## Results

- Model was able to capture the general upward/downward trend in sales
- Forecast for next month's revenue is displayed alongside historical data
- Visualizations clearly show actual vs. predicted values

---

## Visualizations

- **Monthly Sales Trend** – Line chart showing sales over time
- **Forecasting Plot** – Overlay of actual sales, regression fit, last month's prediction, and next month's forecast

---

## Future Improvements

- Apply **Exponential Smoothing / ARIMA** for better time series forecasting
- Use additional features (e.g., product category, region) for multivariate analysis
- Integrate with **Power BI** for interactive dashboards


