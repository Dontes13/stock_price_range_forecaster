# 📈 Stock Price Prediction (LSTM vs GRU)

This project implements and compares two deep learning models — **LSTM** and **GRU** — to predict **next-day Open and Close prices** from historical OHLCV data. Models are built with **PyTorch** and trained on rolling **30-day** sequences.

---

## 🧠 Models
- **LSTM (Long Short-Term Memory):** Captures long-term dependencies in time series.
- **GRU (Gated Recurrent Unit):** Lighter alternative with fewer parameters.

---

## 🔧 Features
- Data preprocessing with **pandas**, **NumPy**, **scikit-learn**
- Sequence windowing (past 30 days → next-day prediction)
- Training & inference with **PyTorch**
- Saved artifacts: **`lstm_model_weights.pth`**, **`scaler.save`**
- Performance comparison using **MSE** (per target)
- Visualizations of actual vs. predicted prices
- Ready to integrate with **Streamlit** (this repo) or **Flask**

---

## 📊 Results
| Model | MSE (Open) | MSE (Close) |
|------|-------------|-------------|
| LSTM | _10.7422_ | _16.8829_ |
| GRU  | _62.9326_ |  _50.9872_ |

LSTM outperformed GRU in both Open and Close price predictions.

!Visualization](path/to/your/graph.png)



---

## 🗂 Project Structure
```
.
├── README.md
├── requirements.txt
├── app.py                  # Streamlit app
├── model.py                # LSTM/GRU definitions
├── lstm_model_weights.pth  # trained weights (PyTorch state_dict)
├── scaler.save             # fitted MinMaxScaler (joblib)
└── forecasting_notebook.ipynb  # training/experiments (optional)
```

---

## 🚀 Quickstart
1) Install dependencies  
```bash
pip install -r requirements.txt
```

2) Run the Streamlit app  
```bash
streamlit run app.py
```

3) Upload a CSV with columns:
```
Open, High, Low, Close, Volume
```
(Feature order must match the scaler used during training.)

---

## 🧪 Example Output
```
Actual Open: 111.20, Pred Open: 110.68 | Actual Close: 109.14, Pred Close: 111.37
Actual Open: 110.60, Pred Open: 110.17 | Actual Close: 110.73, Pred Close: 111.18
...
```

---

## 💾 Deployment
- Load **`lstm_model_weights.pth`** and **`scaler.save`**
- Deploy with **Streamlit** (this repo) or **Flask**
- Optional: containerize with **Docker** for cloud deployment

---

## 📚 Tech Stack
- Python 🐍
- PyTorch 🔥
- NumPy & Pandas
- scikit-learn
- Matplotlib & Seaborn

---

## 🚀 Live Demo
Try the model live on Streamlit: [Stock Price Forecaster Demo]([https://your-streamlit-link.streamlit.app/](https://time-series-forecast-model-pao9jxpoaqkjfwkrhgj6bl.streamlit.app/))

---

## 👤 Author
**Dante Santurian** – University of Michigan

