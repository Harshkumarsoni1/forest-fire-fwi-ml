<img width="448" height="417" alt="image" src="https://github.com/user-attachments/assets/06d832ad-b89b-4101-8d5a-b6a6475d8f31" />

# Forest Fire Weather Index (FWI) Prediction – ML + Flask

A real‑time Machine Learning web app that predicts **Fire Weather Index (FWI)** using 12 environmental features.

## 🚀 Features
- End-to-end ML pipeline  
- Ridge Regression model  
- StandardScaler preprocessing  
- Flask backend for deployment  
- Clean HTML interface  
- Fully offline working app  

## 📁 Project Structure
```
Ml project 1 Forest/
│
├── app.py
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
├── templates/
│   ├── home.html
│   └── index.html
├── req.txt
└── README.md
```

## 📈 Model Details
- Algorithm: **Ridge Regression**
- Preprocessing: StandardScaler
- R² ≈ 0.82  
- MAE ≈ 2–3  
- RMSE ≈ 3–4  

## 🔢 Input Features (12)
```
day, month, year,
Temperature, RH, Ws, Rain,
FFMC, DMC, ISI,
Classes, Region
```

## ▶️ How To Run
```
python -m venv .venv
.\.venv\Scripts ctivate
pip install -r req.txt
python app.py
```
Then open:
```
http://127.0.0.1:5000/
```

## 💼 Resume Description
Built a complete ML-powered Flask application to predict Fire Weather Index (FWI) from meteorological parameters. Integrated a trained Ridge Regression model with a scalable backend and developed a clean UI for real-time predictions.

## 📌 ATS-Friendly Line
A Flask-based machine-learning web app that predicts Fire Weather Index using 12 engineered environmental features.

