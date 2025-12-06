# 📈 Bitcoin Price Prediction Using LSTM Deep Learning

This project uses a Long Short-Term Memory (LSTM) neural network to predict the closing price of Bitcoin (BTC-USD) based on historical time-series data. It applies essential data preprocessing techniques, builds a deep learning model, evaluates performance, and visualizes actual vs. predicted values.

---

## 🚀 Features
- Fetches historical Bitcoin price data  
- Data preprocessing (scaling, windowing, reshaping for LSTM)  
- LSTM deep learning model for time-series prediction  
- Model training, validation, and evaluation  
- Visualization of original vs. predicted closing prices  
- Easily reproducible Python notebook  

---

## 📊 Tech Stack
- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **scikit-learn**

---

## 🧠 Model Used  
**LSTM (Long Short-Term Memory)**  
A type of recurrent neural network (RNN) ideal for predicting financial time-series data due to its memory-cell architecture.

---

## 🛠️ How It Works

### 1. **Data Loading**
Loads historical BTC-USD prices (CSV or downloaded via `yfinance`).

### 2. **Preprocessing**
- Scaling with `MinMaxScaler`
- Creating time-series sequences
- Splitting train & test sets
- Reshaping to (samples, timesteps, features)

### 3. **Model Architecture**
- Stacked LSTM layers  
- Dense output layer  
- Compiled with Adam optimizer + MSE loss  

### 4. **Training**
Model learns patterns in past price movements.

### 5. **Evaluation**
- RMSE  
- Prediction vs. actual comparison  
- Plot of model performance  

---

## 📈 Output Example

The notebook produces a graph similar to:

- Blue line → Actual Bitcoin prices  
- Red line → LSTM Predicted prices  

---

