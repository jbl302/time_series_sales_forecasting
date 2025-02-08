# Sales Forecasting using Time Series Models

## Project Overview
This project focuses on sales forecasting using historical data from the past five years to predict sales for the next three months. Various machine learning and deep learning models were explored, with Long Short-Term Memory (LSTM) networks yielding the best results. Additionally, a user-friendly interface was developed using Streamlit for easy interaction and visualization.

## Features
- **Data Preprocessing:** Cleaned and transformed historical sales data.
- **Model Implementation:** Applied multiple models, including:
  - ARIMA
  - Artificial Neural Networks (ANN)
  - Various Machine Learning models (Random Forest, XGBoost, etc.)
  - Long Short-Term Memory (LSTM) networks (Best-performing model)
- **Evaluation:** Compared models using performance metrics such as RMSE and MAE.
- **UI Development:** Built a Streamlit-based web application for easy model interaction and forecasting visualization.

## Technologies Used
- **Python Libraries:** Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Statsmodels
- **Time Series Modeling:** ARIMA, LSTM, ANN, ML models
- **UI Development:** Streamlit
- **Visualization:** Matplotlib, Seaborn, Plotly

## Installation
### Prerequisites
Ensure you have Python 3.7+ installed. Then, install the required dependencies:
```bash
pip install pandas numpy scikit-learn tensorflow statsmodels streamlit matplotlib seaborn plotly
```

## Usage
1. **Prepare Data:** Ensure your dataset follows the correct format.
2. **Train Models:** Run the script to train different models and evaluate their performance.
3. **Deploy UI:** Start the Streamlit app with:
   ```bash
   streamlit run app.py
   ```
4. **View Results:** Interact with the UI to visualize forecasts and compare models.

## Results
- LSTM outperformed other models, providing the lowest RMSE.
- ARIMA showed reasonable performance but was outperformed by LSTM.
- ANN and ML models were tested, but LSTM captured time dependencies more effectively.

## Future Improvements
- Implementing hybrid models for better performance.
- Enhancing data preprocessing with additional feature engineering.
- Deploying the Streamlit app on a cloud platform for remote access.

## Project Links
- **Project Link:** [Streamlit App](https://salesforecasting-mrbel5ajxvfhzpfpptb8a6.streamlit.app/)
- **Dataset Link:** [Kaggle Dataset](https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data)
