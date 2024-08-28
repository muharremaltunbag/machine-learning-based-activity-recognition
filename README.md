# Machine Learning-Based Physical Activity Recognition Using Wearable Sensor Data

## Project Overview

This project focuses on the classification of physical activities using data collected from wearable sensors. The data was gathered using the Trivisio Colibri Wireless unit, which includes IMUs (Inertial Measurement Units) and a heart-rate monitor. The main objective is to develop a machine learning model capable of accurately identifying different physical activities such as walking, cycling, and playing football based on sensor data.

## Research Objective

The primary goal of this project is to build a robust predictive model using machine learning techniques. This model aims to utilize the IMU and heart-rate data to accurately classify various physical activities. The insights derived from this model can be applied in health and fitness applications, helping to optimize wearable devices for real-world use.

## Data Description

The dataset consists of recordings from 9 subjects, each performing 12 core physical activities, with some performing an additional 6 optional activities. Each data file contains 54 attributes, which include:

- **timestamp**: The time at which the data was recorded.
- **activityID**: A unique identifier for each activity.
- **heart-rate bpm**: The heart rate of the subject in beats per minute.
- **IMU readings**: Data from sensors placed on the wrist, chest, and ankle.

## Project Structure

- **data/**: Contains the dataset files used in the analysis.
- **notebooks/**: Jupyter notebooks for data exploration, preprocessing, feature engineering, model training, and evaluation.
- **reports/**: Documents and reports generated during the project.

## How to Run the Project

1. **Clone the repository to your local machine:**

   ```bash
   git clone https://github.com/muharremaltunbag/machine-learning-based-activity-recognition.git
2. Navigate to the project directory:
   cd machine-learning-based-activity-recognition
3.Open the Jupyter notebooks in the notebooks/ directory to explore the data, perform preprocessing, and build the machine learning models.


## Model Development

This project employs various machine learning techniques to classify physical activities based on sensor data. Models such as Random Forest and XGBoost were explored, with hyperparameter tuning conducted using GridSearchCV. Class imbalance was addressed using SMOTE (Synthetic Minority Over-sampling Technique).

## Results

The XGBoost model emerged as the best-performing model, showing high precision and recall across most activity classes. Feature importance analysis highlighted that sensor readings from the hand and ankle were particularly significant in the classification tasks.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

Special thanks to all participants involved in data collection and to the contributors who made this project possible.

/* This README file provides a comprehensive overview of the project in a consistent and professional style. It covers all essential aspects, including the project's objective, data description and model development. */




