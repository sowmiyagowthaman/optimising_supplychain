# optimising_supplychain
AI-powered tool that predicts sales, profit, and late delivery risks using supply chain data. With a simple web interface, it helps businesses make faster, smarter decisions to avoid delays, optimize resources, and boost customer satisfaction.

---

## 📦 Features

- 📈 **Sales & Profit Forecasting**  
  - Models: Holt-Winters, SARIMA, Prophet  
  - Best RMSE: Holt-Winters (most accurate)

- ⚠️ **Late Delivery Risk Prediction**  
  - Models: Random Forest (74.5% accuracy), SVM, XGBoost, KNN  
  - Predicts if an order will arrive late in real-time

- 🌐 **Flask Web App**  
  - Enter order details  
  - Get instant prediction + risk insight  
  - Helps managers take proactive steps

---

## 📁 Project Structure

optimising_supplychain/
-> data -> Put your dataset(s) here  
   └── supply_data.csv

Inside the zip file ← Your Python code 
   ├── forecasting.py
   ├── delivery_risk_model.py
   └── app.py          ← This is your Flask web app

├── report        ← Your final project report (PDF)
│   └── Final_Report.pdf
│
├── README.md           ← The file we just updated
└── requirements.txt    ← Python libraries used in your project



---

## 🛠️ Tech Stack

- Python, pandas, scikit-learn, statsmodels, Flask
- Time-series models: Holt-Winters, SARIMA, Prophet
- ML models: Random Forest, XGBoost, SVM, KNN

---

## 📊 Dataset

- 📍 Source: Kaggle (DataCo Smart Supply Chain Dataset)  
- Contains: Orders, delivery times, product categories, regions, and customer data

---

## 🚀 How to Run

```bash
git clone https://github.com/sowmiyagowthaman/optimising_supplychain.git
cd optimising_supplychain
pip install -r requirements.txt
python src/app.py

