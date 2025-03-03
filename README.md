
Stock Time Series Analysis and Prediction - Jupyter Notebook README

This Jupyter Notebook provides a comprehensive analysis and prediction of stock time series data, 
using a dataset of historical stock prices for 29 of the 30 DJIA companies over the past 12 years.

Dataset:
    - The dataset contains historical stock prices from 2006-01-01 to 2018-01-01.
    - It includes data for 29 of the 30 DJIA companies (excluding 'V').
    - Data is provided in multiple formats:
        - `all_stocks_2006-01-01_to_2018-01-01.csv`: A combined CSV file with all stock data.
        - `all_stocks_2017-01-01_to_2018-01-01.csv`: A smaller CSV file with only the last year's data.
        - `individual_stocks_2006-01-01_to_2018-01-01/`: A directory containing individual stock data files.

Data Columns:
    - Date (yy-mm-dd)
    - Open: Opening stock price
    - High: Highest stock price during the day
    - Low: Lowest stock price during the day
    - Close: Closing stock price
    - Volume: Number of shares traded
    - Name: Stock ticker symbol

Notebook Structure:
    1.  Data Loading and Exploration:
        -   Loading the dataset using pandas.
        -   Exploring the data structure and initial statistics.
        -   Visualizing stock price trends.
        
    2.  Data Preprocessing:
        -   Handling missing values.
        -   Feature scaling using MinMaxScaler.
        -   Preparing data for time series analysis.
        
    3.  Model Building:
        -   Implementation of a Long Short-Term Memory (LSTM) neural network using PyTorch.
        -   Training the LSTM model on the preprocessed data.
        
    4.  Model Evaluation:
        -   Making predictions on the test set.
        -   Inverse transforming the predictions to the original scale.
        -   Visualizing the predicted vs. actual stock prices.
        -   Evaluation of model loss during training.
        
    5.  Visualization:
        -   Plotting the training loss over epochs.
        -   Plotting the actual vs. predicted stock prices.
        

Example Usage:
    -   Load the notebook in Jupyter Notebook or JupyterLab.
    -   Run the cells sequentially to reproduce the analysis and predictions.
    -   Modify the code to explore different aspects of the data or to experiment with different models.

Key Technologies:
    -   Python
    -   pandas
    -   NumPy
    -   PyTorch
    -   Matplotlib

GitHub Repository:
    -   The script used to acquire the data and the modeling codes can be found in this GitHub repository: [Repository Link - Please add the correct link]
    -   The repository will be updated continually, so feel free to star or watch it.

Note:
    -   This notebook focuses on predicting stock prices using LSTM.
    -   The provided visualizations and evaluations give insights into the model's performance.
    -   The model can be further tuned and improved for better accuracy.

