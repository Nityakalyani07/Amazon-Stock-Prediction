# Amazon Stock Prediction using Neural Networks & FBProphet

This project predicts Amazon (AMZN) stock prices using two approaches:
1. Facebook Prophet for time-series forecasting
2. A simple feedforward Neural Network using Keras

## 📂 Project Structure

- `data/`: Contains the AMZN stock historical CSV.
- `notebooks/`: The main Jupyter notebook combining Prophet and Neural Net.
- `src/`: Modular scripts for preprocessing, modeling, and utility functions.
- `results/`: Plots and model outputs.

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/amazon-stock-prediction-nn-fbprophet.git
cd amazon-stock-prediction-nn-fbprophet
pip install -r requirements.txt
```

Then open the notebook:
```bash
jupyter notebook notebooks/amazon_stock_prediction.ipynb
```

## 📊 Tools Used

- Facebook Prophet
- TensorFlow/Keras
- Pandas, NumPy, Matplotlib, Scikit-learn

## 📈 Example Outputs

| FBProphet Forecast | Neural Net Prediction |
|--------------------|-----------------------|
| ![](results/prophet_forecast.png) | ![](results/nn_predictions.png) |
