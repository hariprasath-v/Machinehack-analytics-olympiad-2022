# Machinehack-analytics-olympiad-2022

### Competition hosted on <a href="https://machinehack.com/hackathons/analytics_olympiad_2022/overview">Machinehack</a>

# About

### Create a machine learning model to help an insurance company understand which claims are worth rejecting and the claims that should be accepted for reimbursement.

### The Final Competition score is 0.68081

### Leaderboard Rank is 24

### The Evaluation Metric is Logloss.

### File information
 
 * machinehack-analytics-olympiad-2022-eda.ipynb [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/hari141v/machinehack-analytics-olympiad-2022-eda/notebook)
    #### Basic Exploratory Data Analysis
    #### Packages Used,
        * seaborn
        * Pandas
        * Numpy
        * Matplotlib
* machinehack-analytics-olympiad-2022-model.ipynb [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/hari141v/machinehack-analytics-olympiad-2022-model/notebook)
    #### Data Pre-processing and model. 
    #### Packages Used,
        * Sklearn
        * Pandas
        * Numpy
        * Matplotlib
        * catboost
        * optuna
        * shap
     #### Created catboost classifier model and tuned the hyperparameters by using optuna framework. Model evaluated with Logloss. 
     #### [For more detailed information about the model.](https://github.com/hariprasath-v/Machinehack-analytics-olympiad-2022/blob/main/Approach_Machinehack_analytics_olympiad_2022.pdf)
     

### Catboost model Optimization History - Explains the best score at each trials.
![Alt text](https://github.com/hariprasath-v/Machinehack-analytics-olympiad-2022/blob/main/Model%20Visualization/Catboost%20optuna%20optimization%20history%20for%20100%20trials.png)

### Catboost – SHAP feature importance
![Alt text](https://github.com/hariprasath-v/Machinehack-analytics-olympiad-2022/blob/main/Model%20Visualization/Catboost%20SHAP%20feature%20importances.png)

### Catboost – SHAP top feature impact
![Alt text](https://github.com/hariprasath-v/Machinehack-analytics-olympiad-2022/blob/main/Model%20Visualization/Catboost%20SHAP%20top%20feature%20impact%20the%20model.png)

### Top feature influences for class 1
![Alt text](https://github.com/hariprasath-v/Machinehack-analytics-olympiad-2022/blob/main/Model%20Visualization/Catboost%20SHAP%20top%20feature%20influences%20for%20class%201.png)

### Top feature influences for class 0
![Alt text](https://github.com/hariprasath-v/Machinehack-analytics-olympiad-2022/blob/main/Model%20Visualization/Catboost%20SHAP%20top%20feature%20influences%20for%20class%200.png)

### Overall Train and Validation Logloss
![Alt text](https://github.com/hariprasath-v/Machinehack-analytics-olympiad-2022/blob/main/Model%20Visualization/Catboost%20optuna%20overall%20train%20and%20validation%20logloss.png)
