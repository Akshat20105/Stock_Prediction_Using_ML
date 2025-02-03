# Stock_Prediction_Using_ML

This project uses historical stock data to predict future stock prices using machine learning techniques. The model is built using Python and various libraries such as `yfinance`, `pandas`, `numpy`, `matplotlib`, `scikit-learn`, and `RandomForestRegressor`.

## Features

- Fetch historical stock data using `yfinance`
- Feature engineering with moving averages
- Train-test split and data normalization
- Model training using Random Forest
- Hyperparameter tuning with Grid Search
- Model evaluation and visualization

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Akshat20105/Stock_Prediction_Using_ML.git
   cd stock-price-prediction
   ```

2. Set up a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Start Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

2. Open and run the `Donno.ipynb` notebook to fetch data, train the model, and visualize predictions.