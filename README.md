# Predictive-Analytics-for-YouTube-Ad-View-Prediction-

## Project Description
This project involves predicting YouTube ad views using machine learning models. It utilizes data such as video statistics and engagement metrics to build various predictive models and selects the best performing model for making predictions.

## Requirements

To run this project, you need to have the following Python libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tensorflow`
- `joblib`
- `re` (part of the Python standard library)
- 
## Datasets

The project uses the following datasets:
- `train_lyst1720633807653.csv`: Training data
- `test_lyst1720633807653.csv`: Test data

## Files

- `YouTube_adview_Prediction_AkashShukla_IS_submission.py`: The main script for data processing, model training, and prediction.
- `PredictedAdview.csv`: Output file containing predictions for the test dataset.

## Project Structure

1. **Importing Libraries and Datasets**  
   The script starts by importing necessary libraries and loading the training dataset.

2. **Data Preprocessing**  
   Includes converting columns to numeric values, converting video duration to seconds, and cleaning the dataset.

3. **Exploratory Data Analysis**  
   Visualizations such as heatmaps and histograms to understand the dataset better.

4. **Data Normalization and Splitting**  
   Data normalization using `StandardScaler` and splitting into training and test sets.

5. **Model Training**  
   Various models are trained, including:
   - Linear Regression
   - Support Vector Regressor (SVR)
   - Decision Tree Regressor
   - Random Forest Regressor
   - Artificial Neural Network (ANN)

6. **Model Evaluation**  
   Calculation of Root Mean Squared Error (RMSE) for each model to assess performance.

7. **Saving and Loading Models**  
   The best-performing model is saved and later used to make predictions on the test data.

8. **Prediction Saving**  
   Predictions for the test dataset are saved to `PredictedAdview.csv`.

## Running the Code

1. Ensure that the required libraries are installed.
2. Place the `train_lyst1720633807653.csv` and `test_lyst1720633807653.csv` files in the same directory as the script.
3. Run the `YouTube_adview_Prediction_AkashShukla_IS_submission.py` script to execute the data processing, model training, and prediction steps.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

