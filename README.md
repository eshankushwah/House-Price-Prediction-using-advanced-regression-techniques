# 🏡 House Price Prediction using Advanced Regression Techniques

This project predicts **house prices** using machine learning models such as **Linear Regression, Decision Tree Regressor, and XGBoost**, with a **Streamlit app** for interactive predictions.

The project is inspired by the Kaggle dataset **House Prices: Advanced Regression Techniques** and demonstrates **end-to-end data preprocessing, model training, evaluation, hyperparameter tuning, and deployment**.

---

## 📊 Dataset
- Attributes: mix of **categorical & numerical features** (e.g., overall quality, year built, area).  
- Target variable: **SalePrice**  

---

## ⚙️ Features
✔ Data preprocessing: handling categorical & numerical features  
✔ Model training with **Linear Regression, Decision Tree, and XGBoost**  
✔ Hyperparameter tuning using **RandomizedSearchCV**  
✔ Model evaluation using **RMSE and R² score**  
✔ Comparison of models with visualization  
✔ Final deployment as a **Streamlit web app** where users can:  
   - Upload CSV data  
   - Manually input features  
   - Get **predicted house prices instantly**  

---

## 🧑‍💻 Tech Stack
- **Python**  
- **Pandas, NumPy** – Data processing  
- **Scikit-learn** – ML models & preprocessing  
- **XGBoost** – Gradient boosting regression  
- **Matplotlib** – Data visualization  
- **Streamlit** – Web app deployment  

---

## 🚀 Installation & Setup

1. **Clone this repo:**
   ```bash
   git clone https://github.com/eshankushwah/House-Price-Prediction-using-advanced-regression-techniques.git
   cd House-Price-Prediction-using-advanced-regression-techniques

2. Create a virtual environment (recommended):

python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

✨ XGBoost with hyperparameter tuning performed best.

🌐 Deployment (Future Work)
Currently runs locally with Streamlit.

Can be deployed to Streamlit Cloud, Heroku, or AWS for live demo access.

📂 Project Structure
graphql
Copy
Edit
House-Price-Prediction/
│-- data/                     # Dataset (CSV files)
│-- app.py / web_page_xgboost_custom.py   # Streamlit app
│-- style.css                 # Custom CSS for app
│-- model_training.ipynb      # Jupyter notebook (EDA + training)
│-- requirements.txt          # Dependencies
│-- README.md                 # Project documentation
