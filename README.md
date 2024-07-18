# Gold-Price-Prediction-System-Using-RandomForestRegressor:-
1. Data Loading and Exploration:

The dataset containing gold price data is loaded.
The structure of the dataset is inspected to understand its features and summary statistics.

2. Data Cleaning:

Missing values and duplicated entries in the dataset are checked and addressed.

3. Feature Engineering:

The date column is converted to datetime format.
The year is extracted from the date column to create a new numerical feature, and the original date column is dropped.

4. Handling Outliers:

Outliers in the numerical columns are identified and removed using the Interquartile Range (IQR) method. This helps in reducing the skewness and improving model performance.

5. Data Visualization and Analysis:

Various visualizations, including histograms, bar plots, and pair plots, are created to understand the distribution and relationships between different features.
A heatmap is plotted to visualize the correlation matrix of the dataset, highlighting the relationships between different numerical features.

6. Feature and Target Determination:

The features (independent variables) and target (dependent variable) are separated. In this case, the gold price (GLD) is the target variable, while all other columns are features.

7. Data Scaling:

The features are normalized using Min-Max scaling to bring all values into the same range, which helps in improving the performance of the machine learning model.

8. Data Splitting:

The dataset is split into training and testing sets, with 67% of the data used for training and 33% for testing. This ensures that the model can be trained and evaluated effectively.

9. Model Creation and Training:

A RandomForestRegressor model is created and trained using the training data. This involves fitting the model to the training features and target values.

10. Model Testing:

Predictions are made on the test set using the trained model. These predictions are compared with the actual target values to evaluate the model's performance.

11. Model Evaluation:

The model's performance is evaluated using various metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² score. These metrics are calculated for both the training and testing datasets to assess the model's accuracy and generalization ability.

12. Results Visualization:

A comparison plot between the actual and predicted gold prices is created to visually assess how well the model is performing. This helps in understanding the model's effectiveness in predicting gold prices.
Overall, this approach provides a comprehensive method to build, evaluate, and visualize a gold price prediction system using a RandomForestRegressor. The process includes data preprocessing, outlier handling, exploratory data analysis, feature engineering, model training, and performance evaluation.
