# PRODIGY_ML_01
## Housing Price Prediction
### Description of Each Set of Code
1. Suppress Warnings and Import Packages:
   <br>
    * Suppress warnings and import necessary libraries for data manipulation, visualization, and machine learning.
   <br>
3. Load and Display Data:
   <br>
    * Load the dataset from a CSV file.
      <br>
    * Display the first few rows, shape, and info about the dataset.
      <br>
    * Display summary statistics for the dataset.
      <br>
5. Check for Null Values:
   <br>
    * Check and display the percentage of null values in each column (if any).
      <br>
7. Outlier Analysis:
   <br>
    * Display a boxplot for all features to identify outliers.
      <br>
    * Perform outlier treatment on the 'price' and 'area' columns using IQR method.
      <br>
9. Visualize Pairplot:
    <br>
    * Display pairplot of all features to visualize relationships between them.
      <br>
11. Convert Categorical Variables:
    <br>
    * Convert categorical variables to binary and create dummy variables for 'furnishingstatus'.
      <br>
    * Display the transformed dataset.
      <br>
13. Train-Test Split and Feature Scaling:
    <br>
    * Split the data into training and testing sets.
      <br>
    * Scale numerical features using MinMaxScaler.
      <br>
15. Fit Linear Regression Model:
    <br>
    * Fit a linear regression model using selected features.
      <br>
    * Display the R-squared score on the training set.
      <br>
17. Check for Multicollinearity:
    <br>
    * Display a heatmap of the correlation matrix to check for multicollinearity among features.
      <br>
19. Test Set Preparation and Predictions:
    <br>
    * Scale the test set features and make predictions.
      <br>
    * Display the R-squared score on the test set.
      <br>
21. Plot Actual vs Predicted Values:
    <br>
    * Plot the actual vs predicted values for the test set and display an ideal linear relationship line.

