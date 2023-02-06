# Can we predict the presence of heart disease based upon clinical variables?
## _Overview_
This project aims to perform an exploratory data analysis on a given dataset and compare the performance of three machine learning models: logistic regression, random forest, and decision tree. The goal is to identify the best model for the given dataset based on accuracy, precision, recall, and F1 score.

## __Data__
The dataset used in this project is found on Kaggle [Predicting Heart Disease Using Clinical Variables](https://www.kaggle.com/datasets/thedevastator/predicting-heart-disease-risk-using-clinical-var). It contains [270 rows and 15 columns]. The variables in the dataset include [Age, Sex, Chest pain type, BP, Cholesterol, FBS over 120, EKG results, Max HR, Exercise angina, ST depression, Slope of ST, Number of vessels fluro, Thallium, Heart Disease].

## __Requirements__
The following libraries are required to run the code in this project:

- pandas
- numpy
- sklearn
- matplotlib
- seaborn

## __Methodology__
The methodology followed in this project includes the following steps:

## __Data inspection and cleansing__
### Exploratory Data Analysis:
- Univariate analysis
- Bivariate analysis
- Feature heatmap
- Primary component analysis
### Modelling
- Logistic regression
- Decision tree
- Random forest + Bagging 

## __Results__
The results of this project indicate that the Random Forest model with bagging is the best model for the given dataset with an accuracy of approx 80%.

## __Conclusion__
In conclusion, this project demonstrates the importance of exploratory data analysis and model selection in the field of machine learning. The results show that the Random Forest is the best model for the given dataset based on the evaluation metrics used. Further tuning of the hyperparameters and use of more advanced techniques can potentially improve the performance of the model.
