Household Energy Bill Prediction Using SVM

This project is a complete end-to-end machine learning pipeline to predict household electricity bills based on household features using Support Vector Machine (SVM). It is organized with clean, class-based Python code, and presented in Jupyter Notebook format.





Dataset

File: Household energy bill data.csv



Project Workflow


Phase 1: Data Collection

The dataset was provided in CSV format.



Data Understanding

Loaded the data using a custom DataLoader class.

Displayed shape, data types, null values, and duplicates.

Descriptive statistics were generated.




Univariate &  Bivariate Analysis

Histograms for distribution.

Heatmap to show feature correlation.




Data Preprocessing

Missing values handled using median.

Removed duplicates.

Done using Preprocessor class.



 Data Splitting

Used DataSplitter class to split data into training and test sets.

Target column: amount_paid

Split ratio: 80% train, 20% test




Model Training (SVM)

Created and trained an SVR model using SVMModel class.

Model evaluated using Mean Squared Error and R-squared.


 Model Storage

Saved the model to models/svm_model.pkl using Pickle.



Visualizations

Histograms of each numeric column

Correlation heatmap between features





Results

Metric

Value

R²




Libraries Used

Python

Jupyter Notebook

Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn

Pickle





Author

Name: Hussain akbar
Universty: Superior
Depart: Artifical Intellegence
Prof:Ahmad Hassan 