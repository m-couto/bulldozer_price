# Predicting bulldozer prices

In this project we applied machine-learning to predicting the prices of bulldozers using time-series data.

The project involved the following:
- preprocessing the data, including:
    - parsing dates;
    - dealing with non-numeric features;
    - filling in missing data;
- modelling the data, more specifically training a random forest regressor;
- tuning its hyperparameters;
- evaluating (with RMSLE);
- making predictions with tuned model on test data;
- saving the tuned model.

This project was written in Python and uses Python tools, such as Pandas, NumPy, matplotlib and scikit-learn.


## Explanation of files

The data was retrieved from Kaggle: https://www.kaggle.com/c/bluebook-for-bulldozers/data.

The Jupyter notebook `end-to-end-bulldozer-price-regression.ipynb` is the project report containing the code.
