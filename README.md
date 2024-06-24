# Medical Insurance Cost Prediction using Linear Regression
## Project Overview
This project involves using Linear Regression to predict the medical insurance costs based on various factors such as age, gender, BMI, number of children, smoking status, and region. Accurate prediction of medical insurance costs can help insurance companies set fair premiums and customers to better understand their insurance costs.

## Dataset
The dataset used in this project includes information on different individuals' medical costs along with their demographic and lifestyle information. The key features in the dataset are:
Age
Gender
BMI (Body Mass Index)
Number of children
Smoking status
Region
Insurance charges (target variable)

## Project Steps
### 1. Data Preprocessing
Loading the Dataset: The dataset is loaded into a Pandas DataFrame.
Exploratory Data Analysis (EDA): EDA is performed to understand the distribution of the data, check for missing values, and visualize the features.
Encoding Categorical Variables: Categorical variables like gender, smoking status, and region are encoded into numerical values using one-hot encoding.
Data Splitting: The dataset is split into training and testing sets to evaluate the model's performance.
### 2. Model Construction
Linear Regression Model: A Linear Regression model is constructed using the scikit-learn library.
### 3. Model Training
Training the Model: The model is trained on the training dataset using the fit method.
### 4. Model Evaluation
Performance Metrics: The model's performance is evaluated on the test dataset using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score.
### 5. Results and Analysis
Model Interpretation: The coefficients of the Linear Regression model are analyzed to understand the impact of each feature on the predicted insurance costs.
Prediction Visualization: Predicted vs actual costs are visualized to assess the model's accuracy of 74.4% on test data.

## Conclusion
This project demonstrates the application of Linear Regression in predicting medical insurance costs. By understanding the relationship between demographic and lifestyle factors and insurance costs, insurance companies can set more accurate premiums, and customers can better manage their healthcare expenses.

## Acknowledgements
The dataset used in this project is available from Kaggle. Special thanks to the creators of this dataset for providing the data.
