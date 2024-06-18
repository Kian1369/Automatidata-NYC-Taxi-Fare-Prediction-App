## Project Part 5: Building Regression Models

### Overview

In Course 5, the focus is on building regression models using Python to predict taxi fares. The New York City Taxi & Limousine Commission (NYC TLC) tasked Automatidata with creating a model that can accurately estimate taxi cab fares prior to a ride. This project involves developing and evaluating a multiple linear regression (MLR) model to achieve this goal.

### Objectives

- Develop a multiple linear regression (MLR) model to predict taxi fares.
- Evaluate the model performance using various metrics.
- Ensure the model is generalizable and not overfit to the training data.
- Provide actionable insights and recommendations based on the model.

### Project Tasks

#### Part 1: Model Development

- **Objective:** Create a multiple linear regression (MLR) model.
- **Tasks:**
  - Select and preprocess relevant features.
  - Train the MLR model on the training dataset.
  - Evaluate the model on both training and test datasets.

#### Part 2: Model Evaluation

- **Objective:** Assess the performance and reliability of the regression model.
- **Tasks:**
  - Compute key metrics such as R², MAE, MSE, and RMSE.
  - Analyze the residuals to ensure the model's assumptions are met.
  - Visualize the model's predictions versus actual fare amounts using scatter plots.

#### Part 3: Insights and Recommendations

- **Objective:** Derive business insights and provide recommendations based on the model's findings.
- **Tasks:**
  - Identify the features with the greatest impact on fare amount.
  - Provide recommendations for additional data collection.
  - Suggest potential improvements for the model.

### Key Insights and Recommendations

- **Model Performance:** The MLR model showed high performance on both training and test sets, suggesting it is neither overfit nor overly biased.
  - **R²:** 0.87 (86.8% of the variance is explained by the model)
  - **MAE:** 2.1
  - **MSE:** 14.36
  - **RMSE:** 3.8
- **Feature Impact:** Ride duration has the greatest effect on fare amount, with a mean increase of $7 for each additional minute. However, this is not a reliable benchmark due to high correlation between some features.
- **Data Recommendations:** Request additional data from under-represented itineraries to improve model robustness.
- **Business Impact:** The model can be used to create an app that allows TLC riders to see estimated fares before their ride begins, providing a strong and reliable fare prediction.

### PACE Framework

The project follows the PACE (Plan, Analyze, Construct, Execute) framework to ensure a structured approach to problem-solving.

#### Plan

- **Research Question:** How can we accurately predict taxi fares based on ride features?
- **Data Collection:** Gather data on ride duration, distance, payment type, and other relevant features.

#### Analyze and Construct

- **Model Development:** Build and tune a multiple linear regression model.
- **Feature Selection:** Select features that significantly impact fare amount.

#### Execute

- **Model Evaluation:** Assess the model's performance and ensure it meets necessary assumptions.
- **Communicate Insights:** Present the model's predictions and business implications to stakeholders.

### Conclusion

The MLR model provides a sound framework for predicting taxi fares. By leveraging this model, the NYC TLC can develop an app to estimate fares, enhancing the rider experience and providing valuable insights for future improvements.


### Executive Summary:
![Executive Summary](Course%205%20Automatidata%20Executive%20Summary.png)
