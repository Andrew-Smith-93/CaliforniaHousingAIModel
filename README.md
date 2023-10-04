# California Housing Price Prediction with TensorFlow

## Project Description
This project uses a simple Neural Network built with TensorFlow to predict the median house value based on various features such as longitude, latitude, housing median age, total rooms, total bedrooms, population, households, and median income. The model is trained and evaluated on a dataset of California housing.

## Objectives
- To understand the relationship between house features and median house value
- To train a model that can make accurate predictions of median house value
- To evaluate the model using metrics like MSE, RMSE, MAE, and R-squared

## Installation & Setup
1. Clone this repository

```
git clone https://github.com/Andrew-Smith-93/CaliforniaHousingAIModel.git
```

2. Install the necessary packages

```
pip install pandas tensorflow scikit-learn
```

This will execute the code and output the evaluation metrics at the end.

## Explanation of Metrics
- **MSE (Mean Squared Error)**: Represents the average squared differences between the predicted and actual values.

- **RMSE (Root Mean Squared Error)**: Square root of MSE, in the same units as the target variable.

- **MAE (Mean Absolute Error)**: Represents the average absolute error between the predicted and true values.

- **R-squared**: Represents the proportion of the variance in the dependent variable that is predictable from the independent variables. Value ranges from 0 to 1.

### Sample Metrics from Run
- MSE: 4384331611.576492
- RMSE: 66214.28555513147
- MAE: 47707.9765625
- R-squared: 0.6518582452830095

## License
This project is open source, feel free to use it as you like.
