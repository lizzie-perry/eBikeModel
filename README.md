# eBikeModel
Data on EBikes - to predict duration of trips

**Approach**

Step 1: Prepare the dataset

Use the three datasets and use a series of joins to make one dataset which gives all relevant information on  historical trips, along with information on the docking station the bike is collected from and the weather.

Make use of feature engineering to create any additional features that may be useful in order to gain better understanding and make more sense within the context of the problem.
Step 2: Exploratory Data Analysis

Look into the data and see if there are any data quality issues that need to be addressed or combated, look into the distribution of the data and it's correlation with the target variable
Step 3: Prepare the Dataset for Training

Prepare the dataset to be passed into a model for training, splitting into a training and test set, one-hot-encoding any columns that may require, and drop any columns that are too highly correlated.
Step 4: Train and Evaluate an ML Model

Fit the data into a sklearn regression model (as this is a regression problem).

Evaluate the results using metrics (e.g. MSE and R2) - testing both the training and test set to check for overfitting.

Look into improvements on the model:
- hyper-parameter tuning
- cross validation for overfitting
- testing out different models (e.g. XGBoost and Random Forrest Regressor)
