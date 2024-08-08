# Time-Series-Forecasting

This project demonstrates time series forecasting using LSTM models. The dataset used is monthly milk production data.

## Steps:
1. **Data Loading and Preprocessing**:
   - Load data from `monthly_milk_production.csv`.
   - Normalize the data using `MinMaxScaler`.

2. **Model Building**:
   - Create a sequential model with LSTM and Dense layers.
   - Compile the model with `adam` optimizer and `mse` loss.

3. **Training**:
   - Train the model using `TimeseriesGenerator`.

4. **Evaluation**:
   - Predict and evaluate using MAE, MSE, and R² score.

## Results:
- The model achieved an MAE of 17.08, MSE of 421.82, and R² score of 0.856.

## Dependencies:
- numpy
- pandas
- matplotlib
- statsmodels
- sklearn
- keras
