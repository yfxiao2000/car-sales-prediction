# Car Sales Analysis & Price Prediction

This project analyzes a real-world used car sales dataset to identify price-driving factors and predict selling prices using both statistical and machine learning models.

## Project Highlights

- Cleaned and transformed vehicle listing data (~550K rows)
- Performed Exploratory Data Analysis (EDA): correlation heatmaps, scatter plots, distribution analysis
- Built multiple predictive models:
  - Linear Regression + OLS summary (with p-values)
  - Lasso Regression for feature shrinkage and interpretation
  - Random Forest (MAE: 1005.71, R² Score: 0.9735)
  - XGBoost Regressor (MAE: 969.91, R² Score: 0.9613)
- Forecasted monthly sales trends using an LSTM time series model
- Visualized actual vs predicted performance, residuals, and feature importances

## Project Structure

| File | Description |
|------|-------------|
| `car_sales.ipynb` | Main Jupyter Notebook with full pipeline |
| `car_prices.csv`  | Dataset file |
| `README.md` | Project overview |

## Tools & Libraries

- Python 3, pandas, NumPy
- scikit-learn: Linear, Lasso, Random Forest
- XGBoost
- TensorFlow/Keras: LSTM modeling
- matplotlib, seaborn
- statsmodels for OLS regression

## Model Performance Summary

| Model            | MAE     | R² Score |
|------------------|---------|----------|
| Random Forest    | 1005.71 | 0.9735   |
| XGBoost Regressor| 969.91  | 0.9613   |
| Lasso Regression | 1040.47 | 0.9710   |

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/car-sales-analysis.git
   cd car-sales-analysis
   ```

2. (Optional) Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run Jupyter Notebook:
   ```bash
   jupyter notebook car_sales.ipynb
   ```

---

This project is part of a personal portfolio for showcasing data science, modeling, and storytelling skills.
