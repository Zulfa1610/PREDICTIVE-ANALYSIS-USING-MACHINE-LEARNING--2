Name:Z.Zulfa Fathima



Company:CODTECH IT SOLUTIONS


ID:CT08DJE


Domain:Data Analytics



Duration:Dec 2024 to Jan 2025








# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING--2



PROJECT TITLE:"House Price Prediction Using Random Forest Regressor: A Machine Learning Approach"




Project Objectives


Data Exploration:


Load and explore IPL match data from a CSV file.
Display and understand the schema, structure, and basic statistics of the dataset.


Seasonal Analysis:

Analyze the number of matches played each IPL season and visualize the trend.


Team Performance Analysis:

Identify the number of matches won by each team across seasons.
Study the seasonal performance trends of teams over the years.


Player Performance Analysis:

Determine the top players with the highest "Player of the Match" awards.
Visualize and highlight the contribution of these players.


Venue Insights:

Analyze venues with the highest number of matches hosted.




Toss Decision Analysis:

Explore how toss decisions (bat or field) influenced the outcome of matches for teams.


Visualization:

Use pandas and matplotlib to generate interactive and informative charts for insights.


Libraries Used


PySpark:

Used for distributed data processing.
SparkSession is utilized to create a Spark application and process the data efficiently.
PySpark SQL functions enable querying and grouping operations on data.
Provides methods to load and manipulate large datasets.




findspark:

Ensures that PySpark is easily located and used in the system's Python environment.


pandas:

Used for converting PySpark DataFrames to pandas DataFrames for visualization purposes.
Facilitates easier manipulation and plotting of data.



matplotlib:

Used for creating visualizations such as bar charts, line plots, and horizontal bar charts.
Helps in visualizing trends and insights from the IPL dataset.



seaborn:

Though imported, it is not explicitly used in this code but can complement matplotlib for enhanced visualizations.


Code Explanation


Library Installation and Imports:

Necessary libraries are installed and imported for data handling, visualization, and machine learning.




Load Dataset:

The Boston Housing dataset is loaded from a URL into a pandas DataFrame.


Basic exploration:
Preview the dataset (head()).
Data structure (info()).
Summary statistics (describe()).
Check for missing values.



Correlation Heatmap:

A heatmap of correlations is plotted to identify features most strongly correlated with the target variable (medv).



Feature Selection:

The target variable (medv) is separated from the predictors.
X: Predictor variables.
y: Target variable (house prices).



Data Splitting:

The dataset is split into training (80%) and testing (20%) sets using train_test_split.



Model Training:

A RandomForestRegressor is trained on the training dataset with 100 decision trees (n_estimators=100).


Model Prediction and Evaluation:

Predictions are made on the test set.


Evaluation metrics:
MAE: Average absolute error.
MSE: Average squared error.
RMSE: Square root of MSE for interpretability.
R²: Proportion of variance explained by the model.



Feature Importance:

The importance of each feature in the prediction process is computed and visualized using a horizontal bar chart.




New House Price Prediction:

A hypothetical new house's features are provided in an array.
The model predicts its price, demonstrating its practical application.


OUTPUT:

![image](https://github.com/user-attachments/assets/69b51318-4d70-49ce-bf75-0cb4e75273bd)


![image](https://github.com/user-attachments/assets/ec3503b7-0d3a-4e7e-96f3-c1409795f2ca)
