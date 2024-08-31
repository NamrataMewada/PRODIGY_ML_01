# House Price Prediction using Linear Regression
### Overview
This project involves building a model to predict house prices using linear regression. The model is trained on historical data of house features and their corresponding prices to learn the relationship between them. The trained model can then predict the price of a house given its square footage, number of bedrooms and bathrooms.

### Dataset
Considered features from the dataset for price prediction
* GrLivArea: Square footage of the house
* BedroomAbvGr: Number of bedrooms
* FullBath: Number of bathrooms
* SalePrice: Sale price of the hous

### Model
The project uses a simple linear regression model to predict house prices. The main steps involved are:
* Data Preprocessing: Handle missing values, encode categorical variables, and normalize the features.
* Feature Selection: Choose relevant features for the model.
* Model Training: Train a linear regression model using the training data.
* Model Evaluation: Evaluate the model’s performance using metrics such as MAE, MSE, and R².

### Evaluation
The performance of the linear regression model is evaluated using the following metrics:
* Root Mean Squared Error (RMSE): The square root of the average of the squared differences between predicted and actual values. RMSE provides a measure of the average magnitude of prediction errors in the same units as the target variable.
* Mean Squared Error (MSE): Measures the average of the squares of the errors—i.e., the average squared difference between the estimated values and the actual value.
