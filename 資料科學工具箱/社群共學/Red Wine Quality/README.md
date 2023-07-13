Red Wine Quality
===
[Kaggle Link](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?datasetId=4458&sortBy=relevance&sort=votes)

# Conclusion
## Data Set
1. The quality of this dataset's ranges is **3 ~ 8**, showing a **normal distribution** (total range 0 ~ 10)
2. fixed acidity, residual sugar, density, and PH have no influence on the quality
3. Most features have a large number of outliers
4. There is no missing data, but there're lots of duplicated data(Keep it)

![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/e79fe764-337c-41ee-9457-9620237b1a87)
![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/ba80ef66-cd6a-4eb8-86f8-495b54197aad)
![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/2d4976d2-314f-42d2-b4d4-53ecaf977f86)
![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/f679cd6a-2429-49f7-a657-f82bc352a29e)
![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/5eca6a10-f90f-4400-935f-9df23c41a6e1)
![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/84b8c359-2b59-45ba-8843-5976aa114e52)
![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/71e9034d-7d90-4ac7-aac0-144facd6ba63)

## Baseline Model
1. The quality is turned into 1 (good) and 0 (bad)
2. Build RandomForestClassifier model, cross-validation
3. Test other models ( LogisticRegression, DecisionTreeClassifier, SVC)

![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/a6770c5c-18fd-4b4f-a0cd-18a19aead9d7)

## Feature Engineering
1. Data standardization
2. New Feature: free sulfur dioxide concentration (mso2)
3. Removed unnecessary features (finally decided not to remove)

![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/652d9f38-2fd3-4aea-865c-3e611dfa1a7e)

## Model optimization
1. Random Forest Model Hyperparameter Tuning (rfc_opt)
2. Build XGB model
3. DeepLearning - Pytorch

![image](https://github.com/DrDAN6770/DataSciense-with-Python/assets/118630187/56ebf205-de89-4dad-86e2-f541fc3d455e)

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
