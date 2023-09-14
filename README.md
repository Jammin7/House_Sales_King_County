# House Sales King County

The project involves the analysis of a dataset containing information about house sale prices in King County, which includes Seattle. The dataset covers homes sold between May 2014 and May 2015 and includes various features such as the number of bedrooms, bathrooms, square footage, location coordinates, and more. The objective of the project is to perform data analysis, data wrangling, exploratory data analysis (EDA), model development, evaluation, and refinement.



Here is a summary of the key steps and findings in each module of the project:


Module 1: Importing Data Sets

The dataset is loaded using Pandas from a web address.
The data types of each column are displayed, and the dataset's structure is examined.


Module 2: Data Wrangling

Columns "id" and "Unnamed: 0" are dropped as they are not needed for analysis.
Missing values in the "bedrooms" and "bathrooms" columns are replaced with the mean values of their respective columns.


Module 3: Exploratory Data Analysis

The number of houses with unique floor values is counted, and the results are displayed.
A boxplot is used to analyze price outliers for houses with and without a waterfront view.
A regplot is used to determine the correlation between the "sqft_above" feature and price.
The correlation between all features and the target variable "price" is calculated and displayed.


Module 4: Model Development

Linear regression models are fitted to predict house prices using the features "long" and "sqft_living".
R-squared values are calculated to evaluate the models' performance.


Module 5: Model Evaluation and Refinement

The dataset is split into training and testing sets.
Ridge regression models are fitted using both first-order and second-order polynomial transformations.
R-squared values are calculated to evaluate the models' performance.



Overall Findings:

The data analysis revealed important insights, such as a positive correlation between square footage and price.
The most correlated features with price are "sqft_living," "grade," "sqft_above," and "sqft_living15."
The ridge regression model with second-order polynomial features achieved an R-squared value of approximately 0.70, indicating good predictive performance.
In conclusion, this project demonstrated the use of data analysis, data wrangling, EDA, and machine learning techniques to predict house prices based on various features. The best-performing model incorporated polynomial features and ridge regression. Further refinements and optimizations could be explored to enhance predictive accuracy.
