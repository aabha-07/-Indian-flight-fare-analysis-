# -Indian-flight-fare-analysis-
Exploratory data analysis and machine learning for Indian flight fare prediction.
# Indian Flight Fare Analysis and Prediction

## Overview

This project explores Indian flight fare data using exploratory data analysis (EDA) and machine learning. It investigates how factors such as airline, travel class, departure and arrival times, number of stops, flight duration, and days left before departure relate to ticket prices.

A Random Forest Regression model is developed to predict flight fares based on the available flight information.

## Objectives

- Explore and understand flight fare patterns.
- Compare ticket prices across airlines and travel classes.
- Analyze the relationship between flight duration, booking lead time, stops, and ticket prices.
- Identify useful features for predicting flight fares.
- Build and evaluate a machine learning regression model.

## Dataset

The project uses `Clean_Dataset.csv`, containing approximately 300,153 flight records.

The dataset includes features such as:

- Airline
- Source and destination cities
- Departure and arrival times
- Number of stops
- Flight duration
- Days left before departure
- Travel class
- Ticket price

The `price` column is the target variable for prediction.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Project Workflow

1. Data loading and preparation
2. Data quality checks
3. Exploratory data analysis and visualization
4. Feature preparation and categorical encoding
5. Training and testing data split
6. Random Forest Regression model training
7. Model evaluation using MAE, RMSE, and R²
8. Actual-versus-predicted price visualization
9. Feature importance analysis

## Key Findings

- Flight prices vary considerably between Economy and Business classes.
- Average fares differ across airlines.
- Ticket prices show a relationship with the number of days remaining before departure, although the pattern is not perfectly consistent.
- Differences in class and route composition should be considered when comparing average fares.

## Model Evaluation

The model is evaluated using:

- **Mean Absolute Error (MAE):** Measures the average absolute prediction error.
- **Root Mean Squared Error (RMSE):** Gives greater weight to larger prediction errors.
- **R² Score:** Measures how much variation in ticket prices is explained by the model.

Add the actual metric values from your completed evaluation here.

## Repository Contents

- `Indian_Flight_Fare_Analysis.ipynb` — project notebook containing the analysis, visualizations, and model workflow.
- `flight_fare_model.pkl` — trained model, if included.
- `model_evaluation_results.csv` — evaluation metrics, if included.

## How to Run

1. Open the notebook in Google Colab.
2. Upload the required dataset.
3. Run the notebook cells in order.
4. Review the exploratory analysis, visualizations, and model evaluation results.

## Limitations

The model's predictions depend on the dataset and selected features. The results may not reflect current market prices or every factor affecting actual flight fares. Feature importance indicates predictive usefulness, not causation.

## Future Improvements

- Compare Random Forest with other regression algorithms.
- Tune model hyperparameters.
- Improve model evaluation and validation.
- Develop an interactive interface for flight fare prediction.

## Author

**Aabha R**

B.Tech Computer Science and Engineering (AI & ML)

College of Engineering Chengannur
