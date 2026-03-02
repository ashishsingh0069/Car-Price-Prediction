# 🚗 Car Price Prediction

A deep learning project that predicts used car selling prices using PyTorch.

## 📊 Dataset
[CarDekho Dataset](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)
- 301 rows, 9 features

## 🧠 Model
- 3-layer Neural Network built with PyTorch
- Dropout regularization
- Adam optimizer with ReduceLROnPlateau scheduler

## ✅ Results
| Metric | Value |
|--------|-------|
| R² Score | 0.96 |
| MAE | 0.58 Lakhs |
| RMSE | 0.85 Lakhs |

## 🔧 Features Used
- Car Age, Present Price, Kms Driven
- Fuel Type, Seller Type, Transmission, Owner

## 🚀 How to Run
1. Open the notebook in Google Colab
2. Run all cells top to bottom
3. Use the Gradio UI at the bottom to predict prices

## 📦 Requirements
torch, pandas, numpy, matplotlib, scikit-learn, kagglehub, gradio
