
# Diabetes Prediction System

## Project Overview

The Diabetes Prediction System is a Machine Learning project that predicts whether a person is likely to have diabetes based on medical information.

The project uses a Random Forest Classifier and a Flask web application to provide predictions through a simple user interface.

## Technologies Used

- Python
- Machine Learning
- Random Forest Classifier
- Flask
- NumPy
- Scikit-learn
- HTML and CSS

## Project Files

- `app.py` – Flask application.
- `prediction of diabetes.ipynb` – Jupyter Notebook containing the machine learning workflow.
- `rf_model.pkl` – Trained Random Forest model.
- `scaler.pkl` – StandardScaler object.
- `imputer.pkl` – Missing-value imputer.
- `templates/` – HTML templates.
- `requirements.txt` – Required Python libraries.

## How to Run the Project

1. Clone or download this repository.
2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python app.py
   ```

4. Open your browser and visit:

   `http://127.0.0.1:5000/`

## Model

The project uses a trained Random Forest Classifier for diabetes prediction.

## Disclaimer

This project is developed for educational purposes only. Predictions are not a substitute for professional medical diagnosis.
