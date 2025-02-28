# -Diabetes-Prediction-Model-using-Logistic-Regression

Import Libraries:
Essential libraries like pandas, numpy, matplotlib, seaborn, sklearn are imported for data manipulation, visualization, and machine learning.

Load Dataset:
The diabetes dataset (diabetes.csv) is loaded into a pandas DataFrame (df3), which contains information on different features like glucose levels, BMI, age, etc., with a target variable Outcome (1 for diabetic and 0 for non-diabetic).

Data Cleaning:
Any missing values are removed using dropna() (though the dataset doesn't have missing values).
The isnull().sum() method is used to check for any missing data.

Visualizations:
Several plots are created to understand the dataset:
A histogram showing the distribution of glucose levels.
A histogram comparing the age distribution for diabetic vs non-diabetic individuals.
Scatter plots to explore relationships between glucose levels, diabetes pedigree function, BMI, and the outcome.
A correlation heatmap to show correlations between features and the target variable.
A box plot showing the BMI distribution by diabetes outcome.

Data Splitting:
The dataset is split into features (X3) and target (y3).
The data is divided into training (80%) and testing (20%) sets using train_test_split.

Model Training:
A Logistic Regression model is created and trained using the training data (X_train3 and y_train3).

Model Evaluation:
The trained model is used to make predictions on the test data (X_test3), and the accuracy score is printed.
The confusion matrix is generated to show the performance of the model in terms of true positives, true negatives, false positives, and false negatives.
