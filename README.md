Housing Price Prediction using Regression Analysis with Python
Project Overview
This project demonstrates a regression analysis using the California Housing Dataset to predict median house prices based on several features like average rooms, population, and income levels. Using Python libraries like Scikit-Learn, Pandas, Numpy, Matplotlib, and Seaborn, the project covers the entire machine learning workflow, including data exploration, preprocessing, model training, evaluation, and visualization of results.

Dataset
The dataset used in this project is the California Housing Dataset, which is available directly in Scikit-Learn. This dataset includes various features like:

MedInc: Median income in block group
HouseAge: Median house age in block group
AveRooms: Average rooms per household
AveOccup: Average number of people per household
Latitude and Longitude: Geographical coordinates
The target variable is the median house value for California districts, adjusted to reflect data from the 1990 census.

Project Steps
1. Setup and Imports
Import essential libraries for data handling, model training, evaluation, and visualization.

2. Load and Explore the Dataset
Load the California Housing Dataset and convert it into a Pandas DataFrame.
Display the first few rows and basic statistics.
Generate a heatmap to visualize feature correlations and understand feature relationships.
3. Data Preprocessing
Define X (features) and y (target) variables.
Scale the features using StandardScaler to normalize data for better model performance.
4. Train-Test Split
Split the dataset into training and testing sets with an 80-20 ratio.

5. Model Selection and Training
Use a Linear Regression model to fit the training data.
6. Prediction and Evaluation
Evaluate the model on the test set using Mean Squared Error (MSE) and R² score.
7. Cross-Validation
Perform 5-fold cross-validation to ensure model generalizability and robustness.

8. Visualization of Results
Plot Predicted vs. Actual values to visualize model performance.
Display a Residuals Plot to check the distribution of errors.
