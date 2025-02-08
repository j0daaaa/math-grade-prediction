# Predictive Modelling of High School Students Grade in Portugal
Education plays a crucial role in shaping our lives, fostering intellectual growth and development. This project focuses on predicting the academic performance of high school students in Portugal by building and analyzing machine learning models. Specifically, we utilize Random Forest Regressor and Linear Regressor to develop predictive frameworks. The primary goal is to evaluate the models' effectiveness in forecasting student grades, providing a robust foundation for educational data analysis. The analysis consists of several sections:
### Data Understanding
This section provides an overview of the dataset used in this project. It covers key aspects such as the features included, the target variable, the dataset's size, and the data types.
### Data Cleansing
To ensure data validity, several preprocessing steps are applied, starting with data cleansing. First, outliers are detected and removed using the IQR method to mitigate the impact of extreme values on the modeling process. Next, missing values are imputed using the Missing Completely at Random (MCAR) technique.
### Feature Processing
The next step in preprocessing is feature processing. First, categorical variables are converted into numerical values through label encoding. Then, data scaling is applied using the Min-Max Scaler, a standard normalization technique. Finally, feature selection is carried out based on the Pearson Correlation Coefficient between the predictors and the target variable.
### Model Development
As noted earlier, this study employs Linear Regression and Random Forest Regressor models. To enhance predictive performance, the hyperparameters of the Random Forest Regressor are optimized using the Random Search Cross-Validation technique.
