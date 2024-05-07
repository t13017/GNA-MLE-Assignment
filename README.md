# GNA-MLE-Assignment
# Overview:
The Electricity Price Forecast Assignment is a machine learning project aimed at predicting electricity prices based on various factors such as time, generation sources, and other relevant parameters. The project 
involves data analysis, preprocessing, feature engineering, model training, and deployment of the trained models using a Flask API.

# Project Structure:
The project consists of the following components:

**Dataset**: The dataset (final_energy_dataset.csv) contains information about electricity generation from different sources, forecasts, actual load, and prices. The data is preprocessed to handle missing values, and relevant features are selected for analysis and modeling.

**Jupyter Notebook**: The analysis and modeling tasks are performed in a Jupyter Notebook (electricity_price_forecast.ipynb). The notebook includes steps for data exploration, preprocessing, feature engineering, model training, and evaluation.

**Flask API**: The trained machine learning models (XGBoost, Random Forest) are deployed using a Flask API. The API provides a web interface for users to input relevant parameters and get predictions for electricity prices.

**HTML Template**: The HTML template (index.html) provides a user-friendly interface for interacting with the Flask API. Users can input details such as time, generation sources, and other parameters to obtain predictions for electricity prices.

**Data Analysis and Preprocessing**: The dataset is initially explored to understand its structure and identify any missing values. Missing values are handled using appropriate techniques such as imputation or removal of rows/columns. Feature engineering techniques are applied to extract relevant information from the dataset and create new features if necessary.

# Model Training and Evaluation:
Two machine learning models, XGBoost and Random Forest, are trained using the preprocessed dataset. Hyperparameter tuning is performed using techniques like GridSearchCV to optimize the models' performance. The trained models are evaluated using metrics such as Mean Squared Error (MSE) and R-squared to assess their predictive accuracy.

# Flask API and Web Interface:
The Flask API serves as the backend for making predictions using the trained models. It loads the serialized models and provides endpoints for prediction requests. The HTML template provides a user-friendly interface for users to input parameters and obtain predictions for electricity prices.

# Conclusion:
The Electricity Price Forecast Assignment demonstrates the application of machine learning techniques to predict electricity prices accurately. By leveraging data analysis, preprocessing, and model training, the project provides valuable insights for stakeholders in the energy sector. The deployment of the trained models using a Flask API enables easy access to predictions, facilitating informed decision-making and planning.
