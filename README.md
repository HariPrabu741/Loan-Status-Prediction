
# Loan Status Prediction

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. 

## 🛠 Programming language and packages

- Python
- NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn, Scipy, Imblearn.




  
## Steps followed for this project

- Importing packages
- Loading Dataset
- Descriptive analysis
- Univariate analysis
- Bivariate Analysis
- Data Cleaning
- Data Preprocessing
- Machine Learning Models
- Model Improvement


  
## Project Description

- Required packages are imported. From kaggle dataset is readed. 
- **Descriptive analysis** - Descriptive analysis is done on data and skewed features are identified. 
- **Univariate analysis** - Visually analysed the outliers. Impact of categories on variables is visualized. By countplot the count of values is visualized. Distribution is visualized by distplot.  
- **Bivariate Analysis** - Visually comparing other features with loan status. Impact of ApplicantIncome, CoapplicantIncome and LoanAmount on Loan_Status is visualized. 
- **Data Cleaning** - Removed the outliers from the data and loan id column is removed.
- **Data Preprocessing** - Checked for null values and assigned values for null values. Converted categorical columns into numerical columns. Handled imbalanced data with SMOTE. Train test split done on data.
- **Machine Learning Models** - LogisticRegression, RandomForestClassifier, GradientBoostingClassifier and DecisionTreeClassifier models are created and the performance of the model is analysed. And the best model RandomForestClassifier model is selected.
- **Model Improvement** - Hyperparameter tuning is done on RandomForestClassifier model. And checked with cross validation score. 

## 🔗 Links
[![portfolio](https://img.shields.io/badge/kaggle-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.kaggle.com/hariprabu)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hariprabu741/)


  