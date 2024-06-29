# F1nalyse
[Kaggle_notebooklink](https://www.kaggle.com/code/insanesrikar/f1-analysis/edit)


![image](https://github.com/sriharsha8991/F1nalyse/assets/91383946/2819a670-5794-47f3-a5d9-d1766d1cd6ce)

## Objective
The main objective of this project is to predict the finishing positions of drivers in Formula 1 races based on historical data and to identify factors that significantly impact race outcomes. This predictive modeling will help teams optimize their strategies under varying conditions.

## Data Preprocessing
Data preprocessing involved several steps to prepare the dataset for modeling:

* Handling Missing Values: Missing data points were imputed where necessary to maintain the integrity of the dataset.
* Outlier Detection and Treatment: Identified and treated outliers to prevent skewing the model results.
* Feature Engineering: Derived new features that are likely to influence race outcomes, such as driver experience and car performance indices.
* Encoding Categorical Variables: Transformed categorical variables using one-hot encoding to prepare them for input into the machine learning model.

## Feature Transformation
To address skewed distributions observed in certain features, transformations were applied:

Log Transformation: Applied to right-skewed distributions to normalize data.
## Exploratory Data Analysis (EDA)
Exploratory Data Analysis was conducted to understand the data better and guide subsequent analysis steps. Key activities and insights include:

Distribution Analysis: Evaluated the distribution of various features such as lap times and pit stop durations. Adjustments such as transformations were made to address skewness.
Correlation Analysis: Assessed the relationships between different features and the target variable (finishing position). This helped identify key features that impact race outcomes.
Visualization: Employed various plots (histograms, box plots, scatter plots) to visualize relationships and distributions. This helped identify trends, patterns, and outliers.
Feature Relationships: Explored how different features like weather conditions and circuit type affect race outcomes. Insights from this analysis were used to enhance feature engineering.

## Model Building and Evaluation
A RandomForest model was developed to predict the finishing positions of drivers. The model was chosen due to its robustness and ability to handle non-linear relationships.

Model Training: The model was trained using historical race data.
Hyperparameter Tuning: Parameters like n_estimators, max_depth, and min_samples_split were tuned to optimize the model.
