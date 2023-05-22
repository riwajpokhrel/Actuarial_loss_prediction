# Actuarial Loss Prediction

#### Exploration, engineering, modeling, prediction and explanation of workers' compensation claims. 

### Data Description 
#### The dataset is downloaded from [Kaggle](https://www.kaggle.com/competitions/actuarial-loss-estimation/data). It includes 90,000 realistic, synthetically generated worker compensation insurance policies, all of which have had an accident. For each record there is demographic and worker related information, as well as a text description of the accident.

## Following steps are taken in this work:

- Missing Value Imputation
- Exploratory Data Analysis
- Encoding Catagorical Variables
- Feature Engineering
- Natural Language Processing for the text column
    - Bag-of-Words model
- Predictive models:
    - Decision Tree 
    - Random Forest
    - Gradient Boosting
    - Stochastic GB
    - AdaBoost
    - XGBoost
    - LightGBM
    - CatBoost"
- Comparison of model performance.

5-fold Cross-Validation and hyper-parameter tuning with Grid Search in each model.
