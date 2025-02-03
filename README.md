# ReneWind-Model tuning

**Overview**

Renewind is a machine learning project focused on predicting wind turbine failures to minimize maintenance costs. Using sensor data, various classification models were built and optimized, with XGBoost emerging as the best performer. A pipeline was implemented to streamline the prediction process.

**Features**

Data Preprocessing: Handling missing values, balancing datasets
Model Building & Tuning: Evaluated multiple ML models, with XGBoost achieving the highest recall (0.85)
Pipeline Implementation: Automating the failure prediction workflow
Dataset

5000+ rows with 41 attributes from wind turbine sensor data
Imbalanced dataset with a minority failure class
Results

**Key predictors**: Features V18, V39, V26, V3, and V10 significantly impact failure prediction
**Final Model:** XGBoost with oversampling performed best
