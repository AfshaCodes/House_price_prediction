# House Price Prediction ML Project

This project predicts house prices using a machine learning model trained on features like location, size, number of bedrooms, bathrooms, and more. It includes data preprocessing, model training, evaluation, and deployment as a Streamlit web application.

## Features
1. **Data Preprocessing**:
   - Handles missing data and outliers.
   - Encodes categorical variables (e.g., location) and scales numerical features.

2. **Model Training**:
   - Trains regression models (e.g., Linear Regression, Random Forest).
   - Evaluates models using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² score.

3. **Model Deployment**:
   - Deploys the trained model via a Streamlit web app for user-friendly house price predictions.

## Prerequisites
- Python 3.x
- Libraries:
  - Data processing: `pandas`, `numpy`
  - Machine learning: `scikit-learn`
  - Visualization: `matplotlib`, `seaborn`
  - Deployment: `streamlit`

## How to Run

### Step 1: Setting up the Environment
1. Install Python 3.x.
2. Install required dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn streamlit
