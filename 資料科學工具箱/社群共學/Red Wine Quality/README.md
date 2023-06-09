﻿Red Wine Quality
===
[Kaggle Link](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?datasetId=4458&sortBy=relevance&sort=votes)

# Conclusion
## Data Set
1. The quality of this dataset's ranges is **3 ~ 8**, showing a **normal distribution** (total range 0 ~ 10)
2. fixed acidity, residual sugar, density, and PH have no influence on the quality
3. Most features have a large number of outliers
4. There is no missing data, but there're lots of duplicated data(Keep it)
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

![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/fd5413e4-556a-49cc-b666-4df1c075af26)


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
