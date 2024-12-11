## Overview

This project focuses on detecting and predicting human stress levels using Artificial Neural Networks (ANN). By leveraging machine learning techniques, the system can analyze patterns in physiological or behavioral data and predict the stress level of individuals effectively.

The application is built using Python for the backend, with a Django web framework to serve as the front end, providing users with an intuitive interface to interact with the system.

## Features

User Authentication: Secure user registration and login functionality.

Data Input: Accepts physiological/behavioral data (e.g., heart rate, skin temperature, activity level).

Stress Prediction: Uses an ANN model to predict stress levels based on input data.

Dashboard: Provides users with a graphical representation of their stress trends over time.

Responsive UI: A modern and user-friendly interface.

## Technologies Used
## Backend:

Python

Django Framework

TensorFlow/Keras (for ANN model)

## Frontend:

HTML, CSS, and JavaScript

Bootstrap Framework

## Database:
SQLite (default Django DB) / MySQL (optional)

## ANN (Artificial Neural Network)
Data Input: ANN processes physiological and behavioral data like heart rate, skin temperature, and activity levels.

Feature Scaling: Input data is normalized to ensure consistent feature scaling for effective model training.

Input Layer: Accepts multiple data features as predictors of stress levels.

Hidden Layers: Detects complex patterns and relationships in the input data for accurate stress prediction.

Output Layer: Provides stress predictions, such as Low, Medium, or High levels.

Training Process: The model is trained using labeled datasets with known stress levels and features.

Optimization: Backpropagation and optimizers like Adam are used to reduce prediction errors.

## Future Enhancements

Integrating real-time data collection using wearable devices.

Expanding the model for broader datasets and better accuracy.

Adding features like meditation recommendations or stress relief exercises.


