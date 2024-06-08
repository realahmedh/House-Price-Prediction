

# House Price Prediction

This project aims to predict the prices of houses using two different machine learning approaches: AutoKeras and Random Forest.

## Dataset

The dataset used for this project is the Boston Housing Dataset, which contains information about various attributes of houses in Boston. The dataset has 506 instances and 13 attributes, including median value of owner-occupied homes in $1000s (target variable).

## AutoKeras Implementation

The AutoKeras implementation can be found in the `AutoKeras Implementation` folder. The implementation uses the AutoKeras library to automate the machine learning pipeline and find the best model for the given dataset.

### Steps

1. Load the dataset and split it into train and test sets.
2. Initialize the AutoKeras object and set the hyperparameters for the model.
3. Train the model using the train set.
4. Evaluate the model on the test set.


## Random Forest Implementation

The Random Forest implementation can be found in the `Random Forest Implementation` folder. The implementation uses the scikit-learn library to train a Random Forest model on the dataset.

### Steps

1. Load the dataset and split it into train and test sets.
2. Initialize the Random Forest object and set the hyperparameters for the model.
3. Train the model using the train set.
4. Evaluate the model on the test set.


## Conclusion

Both the AutoKeras and Random Forest implementations achieved good results in predicting house prices on the Boston Housing Dataset. The AutoKeras implementation automates the process of finding the best model for the given dataset and hyperparameters, while the Random Forest implementation is simpler and easier to interpret. The choice of implementation depends on the specific needs of the project.
