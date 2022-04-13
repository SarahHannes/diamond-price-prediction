# Diamond Price Prediction <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/SarahHannes/diamond-price-prediction/main/diamond_price_prediction.html">[Code]</a>

Predict diamond price using simple feedforward neural network.

## Data preprocessing

- Transform all categorical features into numerical using OrdinalEncoder from Sklearn
- Feature normalization using RobustScaler from Sklearn

## Model architecture

- Input layer + 5 Dense hidden layers + 1 Dense output layer
- Trained for 100 epochs
- Last validation mean absolute error is 265.9
<img src="plot/model.png" width="340">
<img src="plot/mean_absolute_error.jpg" width="800">
