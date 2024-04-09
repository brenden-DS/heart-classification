# Heart Disease Prediction Model

This repository contains a machine learning model for predicting heart disease based on a dataset of various health and lifestyle factors. The model uses supervised learning techniques to analyze the dataset and make predictions about the likelihood of an individual having heart disease.

## Dataset Features

The dataset used for training and testing the model contains the following features:

1. **Age**: The age of the individual in years.
2. **Sex**: The gender of the individual (0 = female, 1 = male).
3. **CP (Chest Pain Type)**: The type of chest pain experienced by the individual (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic).
4. **Trestbps (Resting Blood Pressure)**: The individual's resting blood pressure (in mm Hg) upon admission to the hospital.
5. **Chol (Serum Cholesterol)**: The individual's serum cholesterol level in mg/dl.
6. **FBS (Fasting Blood Sugar)**: The fasting blood sugar level of the individual (> 120 mg/dl = 1, <= 120 mg/dl = 0).
7. **Restecg (Resting Electrocardiographic Results)**: The results of the resting electrocardiogram (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy).
8. **Thalach (Maximum Heart Rate Achieved)**: The individual's maximum heart rate achieved.
9. **Exang (Exercise Induced Angina)**: Whether the individual experiences exercise-induced angina (1 = yes, 0 = no).
10. **Oldpeak (ST Depression Induced by Exercise Relative to Rest)**: The amount of ST depression induced by exercise relative to rest.
11. **Slope**: The slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping).
12. **Ca (Number of Major Vessels Colored by Fluoroscopy)**: The number of major vessels colored by fluoroscopy (0-3).
13. **Thal**: A blood disorder called thalassemia (3 = normal, 6 = fixed defect, 7 = reversable defect).

## Usage
To use the heart disease prediction model, simply clone the repository and run the provided Python script. The model takes the input data based on the features mentioned above and provides a prediction regarding the likelihood of the individual having heart disease.

Feel free to contribute to the improvement of the model or the dataset by opening issues or pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
