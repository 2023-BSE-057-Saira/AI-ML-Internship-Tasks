# Task 6: House Price Prediction

## Objective

The objective of this project is to predict house prices based on various property features such as area, number of bedrooms, bathrooms, parking spaces, furnishing status, and other housing attributes.

A machine learning regression model is developed to estimate house prices and evaluate prediction performance using standard regression metrics.

---

## Dataset Used

**Dataset Name:** Housing Dataset

### Features

The dataset contains the following attributes:

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

### Target Variable

* Price

The target variable represents the selling price of a house.

---

## Model Applied

**Machine Learning Algorithm:**

* Linear Regression

**Libraries Used:**

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

---

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the housing dataset.
2. Explored dataset structure and statistics.
3. Checked for missing values.
4. Encoded categorical variables using Label Encoding.
5. Selected input features and target variable.
6. Applied feature scaling using StandardScaler.
7. Split the dataset into training and testing sets.

---

## Model Training

The Linear Regression model was trained using the processed housing data.

The model learned relationships between house characteristics and house prices to make future predictions.

---

## Model Evaluation

The model was evaluated using:

### Mean Absolute Error (MAE)

Measures the average prediction error.

### Root Mean Squared Error (RMSE)

Measures prediction accuracy by penalizing larger errors.

### R² Score

Indicates how well the model explains the variance in house prices.

---

## Visualizations

The project includes:

* Actual vs Predicted House Prices Scatter Plot
* Actual vs Predicted Price Comparison Graph
* Feature Importance Analysis using Regression Coefficients

---

## Key Results and Findings

* Successfully built a house price prediction model using Linear Regression.
* The model identified important relationships between housing features and property prices.
* Evaluation metrics demonstrated the effectiveness of the regression model.
* Visualizations provided insights into prediction accuracy and model performance.

---

## Technologies Used

* Python
* Google Colab
* Scikit-Learn
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Conclusion

A House Price Prediction System was successfully developed using Linear Regression.

The project involved data preprocessing, feature engineering, model training, performance evaluation, and visualization. The model demonstrated the practical application of machine learning regression techniques in real estate price estimation and prediction.

