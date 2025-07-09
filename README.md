# sales-forecasting-project

sales Forecasting using Linear Regression
This project demonstrates how to forecast sales revenue using a Linear Regression model in Python. It includes data preprocessing, feature engineering, model training, evaluation, and visualization of predicted vs actual sales.

Technologies Used
Python 3.x

Pandas, NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

 Setup :
 
pip install pandas numpy matplotlib scikit-learn

Workflow Overview:

Load Data Read the CSV file containing sales records.
Clean & Transform Dates Parse Order Date and compute DayNumber as days since earliest order.
Prepare Features Use DayNumber as input feature X and Sales as target variable y.
Model Training Use train_test_split to create data splits and fit a LinearRegression model.
Prediction & Evaluation Predict on the test set and visualize results with scatter and line plots.
Output Plot Save the forecast vs actual plot in the outputs directory.

