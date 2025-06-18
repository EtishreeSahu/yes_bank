# 📈 Yes Bank Stock Price Prediction

This project predicts the closing stock price of Yes Bank using machine learning techniques. It includes data cleaning, exploratory data analysis (EDA), regression modeling, and hyperparameter tuning.

## 🧠 Project Type
EDA + Regression

## 📂 Files Included
- `yesbank_stock_prediction.ipynb` — main code notebook
- `best_rf_yesbank.pkl` — saved best model (Random Forest)
- `README.md` — this file
- `yesbank-stock-prediction.pdf` — optional project PDF (export of notebook)

## 🧪 Tools Used
- Python
- Pandas
- Matplotlib, Seaborn
- Scikit-learn
- GridSearchCV
- Joblib

## 🔍 What I Did
- Loaded Yes Bank stock data
- Cleaned date format and handled missing values
- Visualized closing price, boxplots, and correlation heatmap
- Trained 2 models: Linear Regression & Random Forest
- Tuned Random Forest using GridSearchCV
- Compared performance using R², RMSE, MAE
- Saved best model for future use

## 📊 Results
Linear Regression outperformed Random Forest, achieving R² ≈ 0.99 with low RMSE. The relationship between Open, High, Low and Close was largely linear.

## 🚀 Future Scope
- Add more financial indicators like SMA, RSI, or Volume
- Use more complex models like XGBoost or LSTM
- Predict price trends instead of absolute values

## 👩‍💻 Author
Etishree Sahu
