# Car Price Prediction using Machine Learning

This project involves cleaning and preprocessing a dataset of used car listings, and then using machine learning to predict car prices based on various features.

## Getting Started

1. Clone the repository: git clone https://github.com/Rishika-Pandit/Car-Price-Prediction.git
cd Car-Price-Prediction

2. Install the required libraries using: pip install pandas numpy scikit-learn

3. Download the dataset 'quikr_car.csv' and place it in the project directory.

4. Run the 'car_price_prediction.py' script: python car_price_prediction.py

5. After running the script, you will find the cleaned dataset saved as 'cleaned_car_data.csv'.

## Project Structure

- **car_price_prediction.py**: The main script to preprocess the dataset, perform feature engineering, and train a Linear Regression model to predict car prices.

- **cleaned_car_data.csv**: The cleaned dataset after preprocessing.

## Data Preprocessing

1. Load the dataset using pandas.

2. Clean the dataset by dropping rows with missing values.

3. Convert the 'year' column to integer datatype.

4. Clean the 'Price' and 'kms_driven' columns by removing non-numeric characters and converting to integer datatype.

5. Preprocess the 'name' column by keeping only the first three words.

6. One-hot encode categorical columns using OneHotEncoder.

## Model Training

1. Split the dataset into training and testing sets (80-20 split).

2. Train a Linear Regression model using scikit-learn's `LinearRegression()`.

3. Create a pipeline with data preprocessing and model training.

4. Evaluate the model using the R-squared (R2) score on the testing set.

## Predictions

1. Predict car prices using the trained model.

2. Example prediction for a specific car configuration is provided at the end of the script.
