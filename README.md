# heart_disease
# Data Analytics Project - Predicting Heart Disease

This repository contains a data analytics project aimed at predicting the presence of heart disease based on various patient attributes. The project utilizes machine learning models such as Logistic Regression, Decision Tree, and Random Forest to perform predictive analysis.

## Dataset

The dataset used in this project consists of the following columns:

- Age: The age of the patient.
- Sex: The gender of the patient.
- Chest_pain: The type of chest pain experienced by the patient.
- Rest_BP: The resting blood pressure of the patient.
- Cholestrol: The cholesterol level of the patient.
- Fasting_Blood_Sugar: Whether the fasting blood sugar of the patient is above or below a certain threshold.
- Rest_ECG: The resting electrocardiographic results of the patient.
- MAX_HeartRate: The maximum heart rate achieved by the patient.
- Exercise_Angina: Whether the patient experiences exercise-induced angina.
- ST_depression_oldpeak: ST depression induced by exercise relative to rest.
- Slope_oldpeak: The slope of the ST segment during exercise.
- Thalium_stress_result: The result of the thallium stress test.
- Target: The presence of heart disease (0 = no, 1 = yes).

## Project Structure

The project is organized as follows:

- `data`: Contains the dataset used for training and testing the models.
- `visulization`: Jupyter notebooks with data exploration, preprocessing, and model development.
- `pipeline`: Trained models saved in pickle format for future use.
- `README.md`: Provides an overview of the project and instructions for usage.

## Usage

To reproduce the results of this project or use the trained models, follow these steps:

1. Clone the repository.
2. Install the required dependencies.
3. Navigate to the  directory and run the Jupyter notebooks in the specified order.
4. Follow the instructions provided in each notebook for data exploration, preprocessing, and model development.
5. Trained models can be found in the directory and can be loaded for further analysis or predictions.

Please note that the provided dataset is for demonstration purposes only. If you wish to use your own dataset, ensure that it follows a similar structure and column names.

## Contributing

Contributions to this project are welcome. Feel free to open issues for suggestions, bug reports, or feature requests. If you would like to contribute code, please fork the repository and create a pull request with your changes.

## Acknowledgments

I would like to acknowledge the sources of the dataset used in this project. Special thanks to the data providers and researchers who have contributed to the field of heart disease prediction.
