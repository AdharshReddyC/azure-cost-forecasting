# Azure Cost Forecasting

Forecasted Azure cloud costs using time series models (SARIMA and Prophet), with Prophet delivering the best accuracy.

## 📂 Dataset
The dataset can be downloaded from the following link:
[Azure Cost Dataset](https://drive.google.com/file/d/1qmEJ5vRCYtL0ao6xd8qMnjyJ4c-9Ip3a/view?usp=sharing)

## 📝 Problem Statement
The objective of this project is to predict future Azure cloud costs using historical billing data. The goal is to create an accurate forecast to help optimize cloud expenditure and improve budget planning.

## 📊 Approach
1. **Data Preprocessing**:
   - Cleaned and formatted date and cost fields.
   - Handled missing values and outliers.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized cost trends and seasonality.
   - Analyzed monthly and weekly patterns.
3. **Modeling**:
   - Built SARIMA and Prophet models for forecasting.
   - Tuned hyperparameters to improve model performance.
4. **Evaluation**:
   - Compared models using MSE, RMSE, and MAPE.
   - Prophet model outperformed SARIMA in terms of accuracy.

✅ **Best Model:** Prophet

## 📌 Key Insights
- Prophet model effectively captured cost seasonality and trend patterns.
- Weekly seasonality played a significant role in improving forecast accuracy.
- Forecasting accuracy was enhanced by tuning hyperparameters.

## 🛠️ Tools Used
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Statsmodels (SARIMA)
- Prophet

## 💡 Future Work
- Explore deep learning models (LSTM, GRU) for further improvements.
- Incorporate additional cost drivers for more granular predictions.

---
© 2025 Adarsh
