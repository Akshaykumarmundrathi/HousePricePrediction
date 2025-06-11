
# House Price Prediction using Linear Regression

This project demonstrates how to predict house prices using a linear regression model. The code includes data cleaning, visualization, model training, evaluation, and prediction for a specific house profile. It is designed to work with a dataset containing house features such as number of bedrooms, space, rooms, lot size, tax, bathrooms, garage spaces, and condition, with 'Price' as the target variable.

## Features

- **Data Cleaning:** Handles missing values by listwise deletion.
- **Visualization:** Includes scatter plots for each predictor vs. price and a correlation heatmap.
- **Model Training:** Uses scikit-learn’s `LinearRegression` to fit the model.
- **Evaluation:** Computes R², MAE, and RMSE for model performance.
- **Prediction:** Predicts the price for a given house profile.
- **Visualization of Results:** Plots actual vs. predicted prices and residuals.

## Requirements

- **Python 3.x**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **scikit-learn**

## Installation

1. **Clone the repository:**
   ```
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction
   ```
2. **Install the required packages:**
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

## Usage

1. **Prepare your data:**  
   Place your CSV file (e.g., `house_data.csv`) in the project folder. The code expects columns: `Price`, `Bedroom`, `Space`, `Room`, `Lot`, `Tax`, `Bathroom`, `Garage`, and `Condition`.
2. **Run the script:**
   ```
   python house_price_prediction.py
   ```
   (Alternatively, use a Jupyter notebook with the provided code.)
3. **Review the output:**  
   - **Visualizations:** Scatter plots (each predictor vs. price), correlation heatmap, actual vs. predicted price plot, residuals plot.
   - **Model metrics:** R² (coefficient of determination), MAE (Mean Absolute Error), RMSE (Root Mean Squared Error).
   - **Predicted price:** For a sample house profile.

## Example Data

The code expects a CSV file with the following columns:
- **Price**
- **Bedroom**
- **Space**
- **Room**
- **Lot**
- **Tax**
- **Bathroom**
- **Garage**
- **Condition**

## Output

- **Visualizations:**  
  - Scatter plots for each predictor vs. price.
  - Correlation heatmap.
  - Actual vs. predicted price plot.
  - Residuals plot.
- **Metrics:**  
  - R² (coefficient of determination)
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
- **Prediction:**  
  - Predicted price for a sample house (e.g., Bedroom: 3, Space: 1500, Room: 8, Lot: 40, Tax: 40000, Bathroom: 2, Garage: 1, Condition: 0).

## Sample Prediction

For a house with:
- **Bedroom:** 3  
- **Space:** 1500  
- **Room:** 8  
- **Lot:** 40  
- **Tax:** 40000  
- **Bathroom:** 2  
- **Garage:** 1  
- **Condition:** 0 (bad)

The model predicts the price as shown in the output.

## License

This project is open source and available under the MIT License.
