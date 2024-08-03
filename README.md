# Car Price Prediction using Machine Learning

This project involves building a machine learning model to predict the selling prices of used cars. The dataset contains various features such as the car's age, present price, kilometers driven, fuel type, seller type, and transmission type. The main steps involved in this project are data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation.

## Steps

1. **Data Preprocessing**:
   - Loaded the dataset and inspected its structure.
   - Removed the 'Car_Name' column as it is not required for prediction.
   - Converted the 'Year' column to 'Age' of the car.
   - Identified and removed outliers to ensure a cleaner dataset.
   - Checked for and handled any missing values.

2. **Exploratory Data Analysis**:
   - Visualized the distribution of numerical features using box plots.
   - Analyzed relationships between features and the target variable ('Selling_Price') using scatter plots and strip plots.
   - Generated a correlation matrix to understand the relationships between features.

3. **Feature Engineering**:
   - Converted categorical features ('Fuel_Type', 'Seller_Type', 'Transmission') into numerical values using one-hot encoding.

4. **Model Building**:
   - Split the dataset into training and testing sets.
   - Normalized the data to ensure better model performance.
   - Trained a Linear Regression model on the training data.

5. **Model Evaluation**:
   - Evaluated the model using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared score.
   - Performed cross-validation to validate the model's performance.
   - Compared the actual and predicted selling prices using bar plots.

This project provides a comprehensive approach to predicting car prices using linear regression, ensuring the model is well-validated and provides meaningful insights.
