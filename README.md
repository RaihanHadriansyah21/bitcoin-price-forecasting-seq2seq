# ₿ Bitcoin Price Forecasting using Seq2Seq LSTM and TensorFlow

## 📌 Overview
This project focuses on Bitcoin price forecasting using Deep Learning approaches with Seq2Seq LSTM architecture and TensorFlow.

The model was developed to perform multivariate time series forecasting by utilizing historical Bitcoin market data along with several technical indicators such as:
- RSI (Relative Strength Index)
- MACD Histogram
- Trading Volume
- Closing Price

In addition to building forecasting models, this project also explores statistical time series analysis to better understand temporal patterns before the training process.

---

## 🚀 Project Highlights
✅ Multivariate Time Series Forecasting  
✅ Baseline LSTM & Seq2Seq LSTM Architecture  
✅ Encoder-Decoder Sequence Learning  
✅ Time Series Decomposition Analysis  
✅ ACF & PACF Statistical Analysis  
✅ Forecast Visualization & Inference  
✅ TensorFlow / Keras Implementation  
✅ Multi-step Future Prediction  

---

## 🧠 Model Architecture

### Baseline Model
The initial model uses a standard LSTM architecture as the forecasting baseline.

### Seq2Seq LSTM Model
The primary model implements:
- Encoder-Decoder Architecture
- Sequence-to-Sequence Learning
- Multi-step Forecasting

This approach enables the model to learn complex temporal sequence patterns from Bitcoin price data.

---

## 📊 Dataset
The dataset contains historical Bitcoin market data and technical indicators used for forecasting experiments, including:
- Close Price
- Volume USDT
- RSI
- MACD Histogram

The dataset is utilized for:
- sequence modeling
- feature engineering
- forecasting experiments
- statistical analysis

---

# 📈 Exploratory & Statistical Analysis

## 🔥 Correlation Heatmap
Feature correlation visualization used to analyze relationships between variables in the time series dataset.

![Correlation Heatmap](images/correlation_heatmap.png)

---

## 📉 Time Series Decomposition
Decomposition analysis was performed to separate:
- Trend
- Seasonal Patterns
- Residual Components

This approach helps identify temporal characteristics before the forecasting process.

![Decomposition Analysis](images/decomposition_analysis.png)

---

## 📌 ACF & PACF Analysis
ACF (Autocorrelation Function) and PACF (Partial Autocorrelation Function) analysis were conducted to examine lag dependencies and autocorrelation behavior within the dataset.

![ACF PACF Analysis](images/acf_pacf_analysis.png)

---

# 🤖 Forecasting Result

## Actual vs Predicted Bitcoin Price
Visualization comparing Seq2Seq LSTM forecasting results with actual Bitcoin price values in a multi-step forecasting scenario.

![Inference Seq2Seq](images/inference_seq2seq.png)

---

## 📋 Key Learning Outcomes
Through this project, several important Deep Learning and Time Series concepts were explored, including:
- Sequence Modeling using LSTM
- Encoder-Decoder Architecture
- Multivariate Forecasting
- Statistical Time Series Analysis
- Deep Learning Workflow for Sequential Data
- Forecast Evaluation & Visualization
- TensorFlow-based Forecasting Pipeline

---

# 🛠️ Technologies & Libraries

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Deep Learning | TensorFlow, Keras |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib |
| Statistical Analysis | Statsmodels |
| Machine Learning Utilities | Scikit-learn |

---

# 📂 Project Structure

```bash
bitcoin-price-forecasting-seq2seq/
│
├── dataset/
│   ├── Bitcoin3.csv
│   └── README.md
│
├── images/
│   ├── acf_pacf_analysis.png
│   ├── correlation_heatmap.png
│   ├── decomposition_analysis.png
│   ├── inference_seq2seq.png
│   └── README.md
│
├── model/
│   ├── model_baseline_LSTM.keras
│   ├── model_seq2seq_LSTM.keras
│   └── README.md
│
├── notebook/
│   ├── bitcoin_forecasting_seq2seq.ipynb
│   └── README.md
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/bitcoin-price-forecasting-seq2seq.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Project

Open the following notebook using:
- Google Colab
- Jupyter Notebook

```bash
notebook/bitcoin_forecasting_seq2seq.ipynb
```

---

# 🔮 Future Improvements
Potential future improvements for this project include:
- Transformer-based Forecasting
- Attention Mechanisms
- Real-time Cryptocurrency API Integration
- Web-based Forecast Dashboard
- Probabilistic Forecasting
- Hyperparameter Optimization

---

# 👨‍💻 Author

**Mohammad Raihan Hadriansyah Prasetya**  
Telecommunication Engineering Student  
AI & Machine Learning Enthusiast

---
⭐ If you find this repository useful, feel free to give it a star.
