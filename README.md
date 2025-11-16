# 📈 MSc Final Project – Bitcoin Price Prediction with Sentiment Analysis  
### The Impact of Social Sentiment on Time Series Models for Bitcoin Price Prediction  
🎓 MSc Data Science | Birkbeck, University of London | 2024  
👤 Author: Mohammed Abuzer Khanzade  

---

## 🚀 Project Summary  
This project investigates whether **sentiment analysis improves Bitcoin price forecasting** when combined with traditional time-series models.

ARIMA and SARIMA models were built **with and without sentiment features**, alongside technical indicators, to measure the performance improvement.

> **Sentiment-enhanced SARIMA reduced RMSE by 56.52% and MAE by 21.53% compared to baseline models.**

---

## 🧠 Key Features

✔️ Time Series Models: ARIMA & SARIMA  
✔️ Sentiment Integration (positive, negative, neutral, compound)  
✔️ Technical Indicators (SMA, EMA, RSI, MACD)  
✔️ Full ML pipeline: preprocessing → feature engineering → modelling → evaluation  
✔️ Performance visualizations included  

---

## 📊 Results Summary

| Model                            | RMSE ↓ | MAE ↓ | MAPE ↓ |
|---------------------------------|--------|-------|--------|
| ARIMA (No Sentiment)            | High   | High  | High   |
| **ARIMA + Sentiment**           | **↓ 59.88%** | ↓ — | ↓ — |
| SARIMA (No Sentiment)           | Medium | Medium| Medium |
| **SARIMA + Sentiment (BEST)**   | **↓ 56.52%** | **↓ 21.53%** | **↓ 18.85%** |

📌 Final conclusion:  
➡️ **Sentiment data SIGNIFICANTLY improves forecasting accuracy**  
➡️ **SARIMA + Sentiment = best performing model**

---

## 📁 Project Structure

```
|-- Code/
|   └── Final Notebook.ipynb
|
|-- Dataset/
|-- Results/
|-- requirements.txt
|-- LICENSE
|-- README.md
```

---

## 🔧 Tech Stack

**Languages:** Python  
**Libraries:**  
`pandas`, `numpy`, `matplotlib`, `scikit-learn`, `statsmodels`, `yfinance`, `joblib`

**Tools:**  
Jupyter Notebook, Kaggle Crypto Tweet Dataset, Yahoo Finance API

---

## ⚙️ Installation & Usage

### Clone Repository
```
git clone https://github.com/Abuzer-Khanzade/MSc-final-project-bitcoin-price-prediction-with-sentiment-analysis.git
cd MSc-final-project-bitcoin-price-prediction-with-sentiment-analysis
```

### Create Virtual Environment
```
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
```

### Install Dependencies
```
pip install -r requirements.txt
```

### Run Notebook
```
jupyter notebook
```

➡️ Open:  
**The Impact of Social Sentiment on Time Series Models for Bitcoin Price Prediction.ipynb**

---

## 🧪 Methodology

### 🔹 Data Collection  
- Bitcoin price history (2013-2021) — Yahoo Finance  
- 824,000+ cryptocurrency tweets — Kaggle dataset  

### 🔹 Preprocessing  
- Handling missing values  
- Date alignment  
- Feature scaling (StandardScaler)  

### 🔹 Feature Engineering  
- Technical indicators → SMA, EMA, RSI, MACD  
- Sentiment lag values & rolling windows  

### 🔹 Model Development  
- Baseline ARIMA & SARIMA  
- Sentiment-integrated versions  
- Hyperparameter tuning  

### 🔹 Evaluation  
- Metrics: RMSE, MAE, MAPE  
- Visuals: residuals, predicted vs actual, trend plots  

---

## 🏁 Conclusion

✔️ **Sentiment analysis significantly improves Bitcoin forecasting performance**  
✔️ SARIMA + Sentiment performed best overall  
✔️ Technical indicators further stabilized predictions  
⚠️ Bitcoin price volatility and ARIMA overfitting remain challenges  

Next research directions:
➡️ LSTMs / Transformers  
➡️ Real-time prediction pipelines  

---

## 📜 License  
This project is licensed under the **MIT License**.

---

## 📬 Contact

**Mohammed Abuzer Khanzade**  
📧 mohammedabuzerk@gmail.com  
🏫 Birkbeck, University of London  
