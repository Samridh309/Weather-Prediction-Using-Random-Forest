# Weather Prediction Using Random Forest

This project demonstrates how to use a Random Forest Classifier to predict weather conditions in Seattle based on historical weather data. The model is trained and evaluated using Python's `scikit-learn` library and provides interactive predictions for user-supplied weather parameters.

## Features

- Loads and prepares weather data from a CSV file
- Trains a Random Forest Classifier to predict weather types (e.g., rain, sun, fog)
- Evaluates model performance (accuracy, classification report, confusion matrix)
- Visualizes the confusion matrix for better interpretability
- Displays feature importances
- Provides an interactive CLI for user-driven weather prediction

## Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib

## Usage

1. **Prepare the Data**
   - Place your `seattle-weather.csv` file in the appropriate directory (e.g., `/content` if using Colab).
   - The CSV must contain the columns: `precipitation`, `temp_max`, `temp_min`, `wind`, and `weather`.

2. **Run the Script**

   The script performs the following steps:
   - Loads the weather data
   - Splits data into training and test sets
   - Trains a Random Forest model
   - Evaluates and visualizes the model
   - Prompts the user to enter new weather parameters for prediction

3. **Interactive Prediction**

   After evaluation, the script allows you to input new values:
   - Precipitation (mm)
   - Max Temperature (°C)
   - Min Temperature (°C)
   - Wind Speed (km/h)

   It then predicts the likely weather type and the model's confidence.


## License

This project is provided for educational purposes.

---

*Created using Google Colab and scikit-learn.*
