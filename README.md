# Ind_Proj_Obesity-Multi-Class-Classification--Kaggle

## Screenshot
[screenshot](https://github.com/dmarks84/Ind_Project_Obesity-Multi-Class-Classification--Kaggle/blob/main/obesity_screenshot.png?raw=true)

## Summary
I worked on the I worked on the Multi-Class Prediction of Obesity Risk data set as part of a Kaggle Competition of the same name.  The dataset provided 16 features of mixed data types that we used to predict multi-class/label classification.  I performed exploratory data analysis and considered cluster analysis based on a series of pairplots.  I also utilized a StandardScaler and PCA to engineer a few additional helpful features.  I instantiated several classifier model classes and used GridSearchCV to find the best parameters for each unique model type, and I iterated through each to determine the best model on the validation data (a subset of the training data provided).  The model was refitted with the full set of training data before generating predicitons on the test set and a submission was made to Kaggle.  

## Results
### Model Selected
The "best" model utilized the light gradient boost model with the following parameters: objective set to 'multiclassova'; metrics set ot multi_logloss; and number of classes set to the number of classes possible:7.  

### Scores
The best average accuracy score on the training set with three-fold cross validation was 0.9711, and this led to a score on the validation set of 0.8990.  When this model was applied to the full training and validation set, it scored at 0.9531, and when refitted and then applied to the full training and validation sets, the score increased to 0.9606.  When applied to the test set, Kaggle reported a public score of 0.90715.

## Skills (Developed & Applied)
Programming, Python, Statistics, Correlation Analysis, Numpy, Pandas, Matplotlib, Scikit-learn, Dataframes, Data Modeling, EDA, Data Visualization, Data Reporting, Multi-Class Classification, Classification, Supervised ML, Cross Validation, Grid search
