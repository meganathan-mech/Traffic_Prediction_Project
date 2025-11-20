# 🚦 Traffic Volume Forecasting using LSTM with Attention Model

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![Dataset](https://img.shields.io/badge/Dataset-Metro%20Interstate%20Traffic%20Volume-yellow.svg)

## 📌 Project Overview
This project predicts hourly **traffic volume** for Interstate highways using **Deep Learning models**:
- LSTM
- LSTM with Attention Mechanism

The model learns historical traffic patterns influenced by:
Weather, Time, Holidays

## 📂 Dataset Information
- Metro Interstate Traffic Volume
- 48,204 Rows
- Includes weather description, temperature, snow, holidays & time features

## ⚙️ Technologies Used
- Python, Pandas, NumPy
- TensorFlow/Keras
- Scikit-Learn
- Matplotlib

## 🧠 Models Used
1️⃣ LSTM Baseline  
2️⃣ LSTM + Attention

📈 Attention Model performs better!

## 📈 Results (Approx)
| Model | RMSE | MAE | Best |
|------|------|------|-----|
| LSTM | ~0.059 | ~0.042 | ❌ |
| Attention LSTM | ~0.055 | ~0.038 | ✅ Winner |

### Visual Results
🟦 Actual vs Predicted  
📍 `results/actual_vs_predicted_attention.png`

📊 Model Comparison  
📍 `results/model_comparison.png`

## 📁 Project Structure
Traffic_Prediction_Project/
├── models/
├── results/
├── dataset/
└── README.md

## ▶️ Run in Google Colab
1. Upload dataset into dataset folder  
2. Run training cells  
3. View results  
4. Push to GitHub

## 👨‍💻 Developer
**Meganathan A**
Traffic Prediction Project (2025)
