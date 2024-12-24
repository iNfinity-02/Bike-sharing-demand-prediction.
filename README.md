
# Bike Sharing Demand Prediction

This project aims to predict the demand for bike-sharing systems based on various factors such as weather, season, holidays, and more. The dataset used in this analysis includes bike-sharing data for two years and various features that can influence bike demand, such as time of day, weather conditions, and the type of day (weekend, holiday, etc.).

## Objective

- To predict the total count of bike rentals (dependent variable `cnt`) based on various independent features such as:
  - Season
  - Weather
  - Hour of the day
  - Working day
  - Temperature, etc.

## Dataset

The dataset used for this project consists of various features, including:
- **Season**: The season during which the data was recorded.
- **Weather Situation**: The weather condition at the time of the rental.
- **Hour of the day**: The time of day the rental occurred.
- **Temperature**: The temperature recorded at the time of the rental.
- **Humidity**: The humidity level at the time of the rental.
- **Working Day**: Whether it was a working day or not.
- **Holiday**: Whether it was a holiday or not.
- **Weekday**: The day of the week the rental occurred.

## Tools & Libraries Used

- **Python**: Programming language used for data analysis.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Visualization library for creating plots and graphs.
- **Seaborn**: Statistical data visualization.
- **Scikit-learn**: Machine learning library for regression models and preprocessing.
- **Statsmodels**: For statistical models and VIF analysis.

## Steps Involved

1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables using dummy variables.
   - Scaling the features for better model performance.
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing relationships between features and the dependent variable.
   - Identifying potential outliers and skewness.

3. **Model Building**:
   - Building a linear regression model.
   - Validating assumptions such as normality, linearity, and homoscedasticity using plots like Q-Q plots and residual plots.
   
4. **Model Evaluation**:
   - Evaluating the model using metrics such as Mean Squared Error (MSE) and R-squared.
   - Analyzing VIF (Variance Inflation Factor) to check for multicollinearity.

## Key Insights

- **Season**: Strongly correlates with bike bookings, with peak bookings in specific seasons.
- **Weather Situation**: Weather conditions, especially clear weather, lead to higher bookings.
- **Temperature**: Higher temperatures tend to have higher bike-sharing demand.
- **Weekdays & Working Day**: Demand is generally higher on working days and during the weekdays.
