# Dynamic-Pricing-Strategy-using-PythonDynamic Pricing Strategy using Python
Tools Used and Their Purpose

1. Pandas
Used for data loading, cleaning, and manipulation.
Handled missing values, selected numerical and categorical columns, and managed the data frame through all preprocessing steps.

2. NumPy
Used for fast numerical operations and array manipulation.
Supported mathematical computations such as replacing outliers and converting DataFrames into arrays before training the model.

3. scikit-learn (sklearn)

StandardScaler – normalized numeric features.

train_test_split – divided data into training and testing sets.
Enabled preprocessing and preparation of data for modeling.

4. Plotly (graph_objects and express)
Used to create interactive visualizations:

Correlation heatmap to show relationships between variables.

Scatter plots and box plots for ride cost and duration analysis.

Donut chart showing profitable vs. loss-making rides.

Actual vs. predicted plots to assess model accuracy.

5. Python Custom Functions
A preprocessing pipeline function was written to:

Detect and replace outliers using IQR.

Fill missing values in numeric and categorical columns.

Prepare data for machine-learning tasks.

What the Program Does

Data Preprocessing – Cleans the raw dataset, fills in missing values, and removes outliers.

Visualization – Uses Plotly to explore ride behavior, costs, and variable correlations.

Model Preparation – Encodes categorical features, normalizes numeric ones, and splits data for training/testing.

Prediction and Evaluation – Builds and visualizes predicted vs. actual ride costs to gauge accuracy.

Profitability Analysis – Compares historical vs. dynamically calculated ride prices to identify profit trends.

Summary

The project combines Pandas, NumPy, scikit-learn, and Plotly to create a data-driven pricing model.
It automates data cleaning, performs statistical analysis, and produces interactive plots that reveal how dynamic pricing can improve profitability.
