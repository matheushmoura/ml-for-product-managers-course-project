# Machine Learning Foundations for Product Managers - Final Project

## Project: Predicting Electrical Energy Output of a Combined Cycle Power Plant

This is the final project for the "Machine Learning Foundations for Product Managers" course. The objective of this project is to build a machine learning model to predict the net hourly electrical energy output of a Combined Cycle Power Plant (CCPP) using ambient environmental readings from sensors at the plant.

### Project Overview

The Combined Cycle Power Plant generates power using a combination of gas turbines, steam turbines, and heat recovery steam generators. We will develop a predictive model using a dataset of 9,568 hourly average readings of various environmental conditions, such as temperature, pressure, humidity, and exhaust vacuum, to predict the plant's electrical energy output.

This project will be peer-graded based on the following four key elements:
1. **Modeling Approach**: Correct identification of the type of modeling task, features, and algorithms.
2. **Model Building**: Comparison of at least two different models or combinations of features/hyperparameters using validation techniques.
3. **Model Evaluation**: Selection of an appropriate evaluation metric and calculation of model performance.
4. **Model Interpretation**: Clear communication and interpretation of the model's performance.

### Dataset Description

The dataset consists of 9,568 rows of hourly average readings from sensors at a power plant. The variables include:

- **Temperature (T)**: Ranges from 1.81°C to 37.11°C
- **Ambient Pressure (AP)**: Ranges from 992.89 to 1033.30 millibar
- **Relative Humidity (RH)**: Ranges from 25.56% to 100.16%
- **Exhaust Vacuum (V)**: Ranges from 25.36 to 81.56 cm Hg
- **Net hourly electrical energy output (PE)**: Target variable, ranges from 420.26 to 495.76 MW

### Project Steps

1. **Problem Identification**:
   - Task: Predict the net hourly electrical energy output (regression task).
   - Evaluation Metric: We will use **Root Mean Squared Error (RMSE)** to evaluate the model performance.
  
2. **Feature Selection & Algorithms**:
   - Features: The environmental variables (Temperature, Ambient Pressure, Relative Humidity, Exhaust Vacuum) will be used as input features.
   - Algorithms Considered: We will compare multiple algorithms, including:
     - **Linear Regression**
     - **Random Forest Regression**
     - **Gradient Boosting Machines**
  
3. **Data Splitting & Validation**:
   - Split the data into training and test sets (e.g., 80% training, 20% test).
   - Validation: Use **cross-validation** on the training set to compare model performance.
  
4. **Model Comparison**:
   - Evaluate at least two models with different combinations of features or hyperparameters.
   - Compare the models based on performance on the validation set and select the best one.

5. **Model Evaluation**:
   - Evaluate the final model on the test set using RMSE as the performance metric.
  
6. **Model Interpretation**:
   - Analyze and communicate the performance of the model, including its strengths and any limitations.

### Data Source

The dataset used in this project is publicly available and can be downloaded as a CSV file

### Project Tools

- **Language**: Python
- **Libraries**: 
  - Scikit-learn (for model building and evaluation)
  - Pandas (for data manipulation)
  - Matplotlib (for data visualization)

### Conclusion

In this project, we applied various machine learning techniques to predict the energy output of a Combined Cycle Power Plant using environmental data. By comparing different models and evaluating their performance, we aimed to find the most effective method for predicting power output. This project demonstrates how machine learning can be used to solve real-world regression problems in the field of energy.
