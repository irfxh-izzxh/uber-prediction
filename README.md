# Uber Ride Cancellation Prediction

## Project Overview

This project aims to predict whether an Uber ride booking will be canceled using Machine Learning techniques. The model analyzes booking details, ride information, customer behavior, and driver-related factors to identify cancellation patterns.

## Problem Statement

Ride cancellations can negatively impact both customers and drivers. By predicting cancellations in advance, ride-sharing platforms can take proactive measures to improve customer satisfaction and operational efficiency.

## Dataset Features

The dataset contains the following features:

* vehicle_type
* pickup_location
* drop_location
* avg_vtat
* avg_ctat
* cancelled_rides_by_customer
* cancelled_rides_by_driver
* incomplete_rides
* booking_value
* ride_distance
* driver_ratings
* customer_rating
* payment_method
* booking_frequency

### Target Variable

* is_cancelled

  * 0 = Not Cancelled
  * 1 = Cancelled

## Project Workflow

### 1. Data Collection

* Load dataset
* Explore data structure

### 2. Data Preprocessing

* Handle missing values
* Encode categorical variables
* Feature scaling
* Remove duplicates

### 3. Exploratory Data Analysis (EDA)

* Cancellation distribution
* Feature correlations
* Ride distance analysis
* Driver and customer rating analysis

### 4. Model Building

The following models were trained:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

### 5. Model Evaluation

Evaluation metrics used:

* Accuracy
* Precision
* Recall
* F1-Score
* Cross Validation Score

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Google Colab

## Project Structure

```text
Uber-Ride-Cancellation-Prediction/
│
├── data/
│   └── uber_dataset.csv
│
├── notebooks/
│   └── Uber_Cancellation_Prediction.ipynb
│
├── models/
│   └── xgboost_model.pkl
│
├── README.md
│
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Uber-Ride-Cancellation-Prediction.git
```

Move into the project folder:

```bash
cd Uber-Ride-Cancellation-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

Open the notebook:

```bash
jupyter notebook
```

or

```bash
python app.py
```

## Results

The XGBoost model achieved the best performance among all tested models and provided reliable ride cancellation predictions.

## Future Improvements

* Hyperparameter tuning
* Real-time prediction API
* Deployment using Flask or Streamlit
* Advanced feature engineering
* Deep Learning models

## Author

**IRFANA IZATH**




