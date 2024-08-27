# Ml_assignment
1. Data Exploration
Objective: To gain initial insights into the Iris dataset.

Explanation: Data exploration involves examining a dataset to understand its structure and key characteristics. In this program, we use the Iris dataset, which is a classic dataset in machine learning featuring measurements of Iris flowers' sepals and petals. The dataset includes the following steps:

Loading the Dataset:

The Iris dataset is loaded from scikit-learn. It contains both feature data (sepal and petal measurements) and target labels (species of the Iris flowers).
Creating a DataFrame:

A Pandas DataFrame is constructed to organize the data and facilitate analysis. The DataFrame includes columns for each feature and an additional column for species names.
Displaying Initial Data:

The first five rows of the DataFrame are displayed to provide a quick view of the data and its format.
Summary Statistics:

Basic statistics (mean, standard deviation, min, and max) are computed for each feature to understand their distributions and central tendencies.
2. Data Splitting
Objective: To prepare the Iris dataset for model training and evaluation by splitting it into training and testing sets.

Explanation: Data splitting is crucial for building and evaluating machine learning models. It involves partitioning the dataset into separate subsets for training and testing to assess the model’s performance on unseen data. This program performs the following steps:

Loading the Dataset:

The Iris dataset is loaded, including feature data and target labels.
Splitting the Data:

The dataset is divided into training and testing sets using an 80-20 split. This means that 80% of the data is used to train the model, and 20% is reserved for testing its performance.
Displaying Sample Counts:

The number of samples in both the training and testing sets is printed to understand the distribution of data.
3. Linear Regression
Objective: To fit a linear regression model and evaluate its performance using a synthetic dataset.

Explanation: Linear regression is a statistical method used to model the relationship between a dependent variable and one or more independent variables. In this program, we use a synthetic dataset to demonstrate linear regression:

Generating Synthetic Data:

A dataset with features such as YearsExperience and Salary is created. The relationship between these features is modeled with some added random noise.
Creating a DataFrame:

A Pandas DataFrame is used to store and manipulate the synthetic data.
Splitting the Data:

The synthetic dataset is divided into training and testing sets to enable model training and evaluation.
Fitting the Model:

A linear regression model is trained using the training data to predict Salary based on YearsExperience.
Evaluating Performance:

The model's performance is evaluated using Mean Squared Error (MSE) on the test set to measure how well the model predicts Salary.
Visualizing Results:

A plot is generated to visualize the fit of the linear regression model against the actual data points.
These explanations provide a theoretical understanding of each script's purpose and the steps involved in the data exploration, data splitting, and linear regression tasks.




