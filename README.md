# Data Science and Analytics Repository

Welcome to my Data Science and Analytics repository! This collection showcases various projects completed during my coursework. Each project demonstrates different aspects of data analysis and modeling techniques. Please note that there is no version history, as these projects are part of my assignments from the Spring 2024 semester.

## Projects

### 1. Basic Data Analytics: Exploratory Data Analysis (EDA)

In this project, I performed basic data analytics on a CSV dataset, focusing on:

- Loading the dataset and displaying its shape.
- Printing the header and the last few rows to understand its structure.
- Summarizing the dataset's statistical details.
- Providing a concise summary of the DataFrame.
- Adding an index column and displaying the updated shape.
- Identifying unique values in a chosen numerical field.
- Replacing extreme values in the dataset with zero, -1, or `np.NaN`.
- Plotting a histogram of a numerical value for visual analysis.
- Converting a categorical field into a numerical format by creating a new column.
- Standardizing a numerical field using the z-score and creating a new column.
- Filtering for outliers based on a selected criterion and creating a new dataset.
- Sorting the dataset and displaying 15 interesting fields.

### 2. Linear Regression Analysis: Predicting Outcomes

This project involves building a linear regression model to predict a continuous target variable. Key steps include:

- Setting up the project by loading the dataset into a Pandas DataFrame and displaying the first five rows.
- Constructing an evaluation set with five data points and three predictors.
- Performing simple linear regression to predict the target variable using one predictor.
- Visualizing the relationship with a scatter plot and fitting the linear regression model, followed by printing the model’s summary.
- Analyzing the model summary for insights.
- Plotting the regression line and evaluation points for visual representation.
- Addressing multicollinearity by selecting predictors, creating a subset of the dataset, and visualizing relationships using a scatter plot matrix.
- Calculating the Variance Inflation Factor (VIF) for the selected predictors.
- Conducting multiple linear regression analysis to expand the model.

### 3. Advanced Regression Techniques: Logistic Regression and LDA

In this project, I explored advanced regression techniques, including:

- Importing necessary libraries such as NumPy, Pandas, Statsmodels, and scikit-learn for analysis and visualization.
- Implementing Logistic Regression to classify categorical outcomes.
- Utilizing Linear Discriminant Analysis (LDA) for dimensionality reduction and classification tasks.
- Performing model selection and evaluation through cross-validation and analyzing linear model statistics.
- Applying Simple Polynomial Regression to fit non-linear relationships.
- Engaging in a discussion forum to share insights and reflections on the methodologies used.

### 4. Diabetes Prediction Analysis: Modeling and Evaluation

This project focuses on predicting diabetes risk using the Diabetes Dataset from Kaggle. Key steps include:

- Analyzing the dataset containing 768 instances of female patients of Pima Indian heritage, using eight numerical predictors to assess the likelihood of developing diabetes.
- Conducting data preparation, including handling missing values and preparing the dataset for analysis.
- Performing exploratory data analysis (EDA) to visualize trends and assess multicollinearity using scatter plot matrices and the Variance Inflation Factor (VIF).
- Testing multiple models, including Multiple Linear Regression, Lasso Regression, Polynomial Regression, and Decision Tree Regression, with evaluation metrics such as Mean Squared Error (MSE) and R-squared values.
- Selecting the best-performing model based on MSE and interpretability, ultimately choosing the Lasso Regression model for deployment.
- Making predictions with new data and analyzing results to understand the likelihood of diabetes.

## Note

This repository does not include version history, as it consists of individual projects completed during the Spring 2024 semester. Each project serves as a standalone demonstration of data analysis techniques and modeling.

Feel free to explore the individual project folders for detailed implementations and analyses. If you have any questions or would like to discuss the projects, please reach out!
