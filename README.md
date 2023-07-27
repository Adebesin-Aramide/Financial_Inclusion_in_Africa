## Financial_Inclusion_in_Africa
## Objective
The objective is to create a machine learning model to predict which individuals are most likely to have or use a bank account. The models and solutions developed can provide an indication of the state of financial inclusion in Kenya, Rwanda, Tanzania and Uganda, while providing insights into some of the key factors driving individuals’ financial security.
## Exploratory Data Analysis
I performed EDA on this dataset by handling missing values, summary statistics, and also handle the imbalanced column which is my target column
I explored various visuals to show the relationship between the columns in the dataset
## Label Encoding
I had various categorical column in my dataset and had to use the label encoder library in sklearn to convert categorical colimn to numerical column
## Feature Selection
With the use of the feature selection library in sklearn, I made use of the p_values to select the important features in the dataset
## Multcollinearity
I used the variance inflation factor in the stats library to determine if there was any multicollinearity between the independent variable
## Model 
Splitted the dataset into train and test, trained with 80% of the dataset and tested with 20 % of the dataset
Used the logistic Regression model to train my model an also made predictions
The Evaluation metric used is the accuracy score
