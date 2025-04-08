# ML-Project-Phase-2

#Using Machine Learning Models for Predicting Energy Billing Amounts Using Consumer Data

Columns and their description in the dataset:

customer_id: Unique identifier for each customer.
region: Geographic region of the customer.
energy_consumption_kwh: Total energy consumption in kilowatt-hours.
peak_hours_usage: Energy usage during peak hours.
off_peak_usage: Energy usage during off-peak hours.
renewable_energy_pct: Percentage of energy from renewable sources.
billing_amount: Total billing amount.
household_size: Number of people in the household.
temperature_avg: Average temperature.
income_bracket: Income bracket of the household.
smart_meter_installed: Whether a smart meter is installed.
time_of_day_pricing: Whether time-of-day pricing is used.
annual_energy_trend: Annual trend in energy consumption.
solar_panel: Whether solar panels are installed.
target_high_usage: Whether the household is targeted for high usage.
The document is structured as follows:

Data Preparation: Details the steps taken to load, preprocess, and split the dataset.
Model Training and Evaluation: Describes the process of training each model and evaluating their performance using the test data.
Results and Analysis: Presents the evaluation metrics for each model and identifies the best and worst performing models.
Conclusion: Summarizes the findings and provides recommendations based on the analysis.
Data Preparation:

The dataset is loaded using pd.read_csv. The features (X) and target (y) are defined. The dataset is split into training and testing sets using train_test_split.

Model training:

Three different models are trained:

Linear Regression
Random Forest Regressor
Decision Tree Regressor
Best and Worst Models:

The best and worst models are determined based on the R-squared value. The model with the highest R-squared value is considered the best, and the model with the lowest R-squared value is considered the worst.
