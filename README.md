# House Price Prediction Project

Project Description
The goal of this project is to predict the housing prices using a variety of regression techniques. The project uses the California Housing dataset to train models like **Linear Regression**, **Polynomial Regression**, **Ridge**, and **Lasso Regression**. The models are evaluated based on key performance metrics such as MAE, MSE, RMSE, and R².

 ->Dataset
The dataset used in this project is the **California Housing dataset** from `sklearn.datasets`. It contains information about the features of various districts in California, such as:
- MedInc: Median income in the area
- HouseAge: Median age of houses in the area
- AveRooms: Average number of rooms per house
- AveBedrms: Average number of bedrooms per house
- Population: Population of the district
- AveOccup: Average number of residents per household
- Latitude: Latitude of the area
- Longitude: Longitude of the area
- MedHouseVal: Median house value (target variable)

 Installation
To run this project, you will need Python 3.x and the following libraries:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install these dependencies using pip:
Steps to Run the Project

1. Clone the repository:https://github.com/adventurecodeing/House-Price-Prediction
2. Run the Jupyter Notebook `House_Price_Prediction.ipynb`:
3. The project contains code for:
    - Loading and preprocessing the dataset.
    - Training models such as Linear Regression, Polynomial Regression, Ridge, and Lasso.
    - Evaluating models with metrics like MAE, MSE, RMSE, and R².

4. Visualizing the results with scatter plots and residual plots.

-> Evaluation Metrics
The following evaluation metrics were used to assess the models:
- MAE (Mean Absolute Error): The average of the absolute differences between predicted and actual values.
- MSE (Mean Squared Error): The average of the squared differences between predicted and actual values.
- RMSE (Root Mean Squared Error): The square root of MSE.
- R² (Coefficient of Determination): Represents the proportion of the variance in the target variable that is explained by the model.

Potential Improvements
- Feature Engineering: Adding additional features such as location or nearby amenities.
- Advanced Models: Using ensemble models like Random Forest or Gradient Boosting.
- Hyperparameter Tuning: Performing hyperparameter optimization for models like Ridge, Lasso, and Polynomial Regression.

 .






