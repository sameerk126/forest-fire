
![45844forest-fire (1)](https://github.com/sameerk126/forest-fire/assets/81867462/2c909ed0-baa8-4e06-9c22-6f4f1f09771c)

# Forest Fire Predictor Using Machine Learning

forest-fire-predictor/
This repository contains a machine learning web application to predict the risk of forest fires. The app is built with Flask and scikit-learn.

## Usage
The app can be run locally with:
It will be available at http://localhost:5000
Enter input data like temperature, humidity, wind speed etc. and the ML model will predict the probability of a forest fire.

## Data
The model is trained on the [Forest Fires Dataset](https://archive.ics.uci.edu/ml/datasets/Forest+Fires) from UCI Machine Learning Repository. The training data is under `/data`.

## Models
Saved model pickles are under `/models`. This includes:
- `linear.pkl` - Linear Regression
- `ridge.pkl` - Ridge Regression 
- `scaler.pkl` - StandardScaler used to scale the data
See the notebook under `/notebooks` for model training and evaluation.

## Installation
pip install -r requirements.txt
### Requirements

- Python 3.x 
- Libraries: `flask`, `pandas`, `scikit-learn` etc. See `requirements.txt`

### Setting Up
1. Clone the repository 
2. Create and activate a virtual environment
3. Install requirements: `pip install -r requirements.txt`  

## Contributors

Pull requests welcome!
