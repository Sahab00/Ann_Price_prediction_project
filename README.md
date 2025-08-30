# Bitcoin Price Prediction using Artificial Neural Networks (ANN)

## Overview
This project aims to predict Bitcoin prices using Artificial Neural Networks (ANN) with TensorFlow and Keras. It leverages historical Bitcoin price data for training and evaluation.

## Features
- Loads and preprocesses Bitcoin historical price data.
- Normalizes data using MinMaxScaler.
- Trains an ANN model using TensorFlow/Keras.
- Implements Early Stopping and Learning Rate Reduction.
- Visualizes predictions using Matplotlib.

## Installation

### Prerequisites
Ensure you have Python installed along with the necessary libraries:

-> pip install numpy pandas matplotlib tensorflow scikit-learn


### Clone the Repository
git clone https://github.com/Sahab00/Ann_Price_prediction_project.git
cd Ann_Price_prediction_project

```

## Usage
Run the Jupyter Notebook:
jupyter notebook Ann_price_prediction.ipynb
```

Follow the steps in the notebook to load the dataset and train the model.

## Dataset
The dataset used for this project is a CSV file containing historical Bitcoin price data. Ensure that `BTC_USD Bitfinex Historical Data.csv` is available in the project directory.

## Model
The ANN model is built using TensorFlow/Keras and consists of multiple layers:
- Input layer
- Hidden layers with activation functions
- Output layer for price prediction

## Results
The trained model generates Bitcoin price predictions, which are visualized using Matplotlib.

## Contributing
Feel free to fork this repository and improve the model. Pull requests are welcome!

## License
This project is licensed under the MIT License.

