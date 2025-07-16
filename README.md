# 🛒 Sales Forecasting using Machine Learning

## 📌 Project Objective

To explore historical weekly sales data, identify trends and patterns, and forecast future sales for the next 3 months (September–November 2024) using a machine learning approach.

---

## 📁 Project Structure

├── EDA_Notebook.ipynb # Exploratory Data Analysis
├── Forecast_Modeling.ipynb # Feature engineering, model training, forecasting
├── Forecast_Modeling.ipynb # Final 3-month weekly sales forecasts
├── random_forest_model.pkl # Trained ML model for reuse
├── README.md # Project documentation


---

## 🧠 Key Skills Applied

- Time Series Analysis
- Feature Engineering (Lag and Rolling Features)
- Regression Modeling with Random Forest
- Forecast Validation & Accuracy Evaluation
- Data Visualization and Performance Interpretation

---

## 🧰 Tools & Technologies

- **Python**
- **Pandas, NumPy** – Data manipulation and calculations
- **Matplotlib, Seaborn** – Visualizations
- **Scikit-learn** – Modeling and evaluation
- **Joblib** – Model persistence
- **Jupyter Notebook** – Development and documentation

---

## 📊 Forecasting Approach

- Data resampled to **weekly frequency**
- Feature engineering included:
  - Lag features: `lag_1`, `lag_2`
  - Rolling mean: `rolling_3`
  - Temporal features: `month`, `week`, `quarter`, `year`
- Model used: `RandomForestRegressor`
- Validation window: **June – August 2024**
- Forecast window: **September – November 2024**

---

## 📈 Results

### ✅ Validation Performance (Jun–Aug 2024)

| Month  | MAE    | MAPE (%) | Monthly Accuracy |
|--------|--------|-----------|------------------|
| June   | 1326.1 | 75.16%    | 24.8%            |
| July   | 2013.7 | 37.60%    | 62.4%            |
| August |  628.2 | 33.23%    | 66.8%            |

### ✅ Forecast (Sep–Nov 2024)

Forecasted weekly sales range: **~3100 to ~4300 units/week**  
Results stored in `Forecast_Modeling.ipynb`

---

## 🔍 Observations & Learnings

- Model performed best in **August**, struggled with outliers in **June**
- Recursive forecasting enabled step-wise week-by-week prediction
- Accuracy improved by including lag/rolling features

---

## 🚀 Future Improvements

- Use external features: promotions, holidays, events
- Try advanced models: **XGBoost**, **SARIMA**, or **Prophet**
- Incorporate deep learning (e.g., LSTM) for long-sequence dependencies
- Deploy forecast using **Streamlit** or **Power BI dashboard**

---

## 🤝 Author

**ABHISHEK VERMA**  
Data Analyst / ML Enthusiast  
📧 averma8534@gmail.com  
🔗 [LinkedIn]([https://www.linkedin.com/](https://www.linkedin.com/in/abhi-shek--verma/)) | [GitHub]([https://github.com/](https://github.com/Abhi-shek-space))

