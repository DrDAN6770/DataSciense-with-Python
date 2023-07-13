Titanic - Machine Learning from Disaster
===
[Kaggle Link]([https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?datasetId=4458&sortBy=relevance&sort=votes](https://www.kaggle.com/competitions/titanic))

# Conclusion
## Data Set
1. There are 3 columns with missing values, 'Age', 'Cabin', 'Embarked'
2. There are 549 Died and 342 Survived in this dataset
3. Women have a higher survival rate than men (74% > 19%)
4. Higher class have a higher survival rate (63% > 47% > 24%)
5. More than 75% have SibSp
6. Only a few can buy more than 300 $ (3 people)
7. 38 years old is Q3, 65~80 years old is less than 1%
![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/0441f9b5-25b7-4090-9414-e2ddc6ac1a5a)
![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/609716b1-6a53-4505-a0c4-1f21ecdbc2e3)
![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/57bd5875-c95c-4871-90e9-6f152413630f)
![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/5e3315ae-5be1-476f-afdb-8b36edcb38a4)

## Baseline Model
1. The quality is turned into 1 (good) and 0 (bad)
2. Build RandomForestClassifier model, cross-validation
3. Test other models ( LogisticRegression, DecisionTreeClassifier, SVC)
## Feature Engineering
1. Data standardization
2. New Feature: free sulfur dioxide concentration (mso2)
3. Removed unnecessary features (finally decided not to remove)
## Model optimization
1. Random Forest Model Hyperparameter Tuning (rfc_opt)
2. Build XGB model
3. DeepLearning - Pytorch

![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/59224d33-bb94-424a-b8f9-919648bf1c7e)

# Content
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol
12. quality

# Data Extraction
* Download a publicly available dataset
* Describe the dataset
* Think each data values

# Data Pre-processing
* Clean invalid values
* Deal with the missing data
* Creating valid columns
* Modify existing columns

# Data Analysis
* Data Visualization
* Data Exploratory Analysis

# Model building
* Select different Model
* Prediction, Classification
