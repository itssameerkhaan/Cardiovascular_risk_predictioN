# Cardiovascular_risk_predictioN
* TYPE :-Classification

**Congenital heart disease** is one or more problems with the heart's structure that exist since birth. Congenital means that you're born with the condition. Congenital heart disease in adults and children can change the way blood flows through the heart.
Cardiovascular diseases (CVDs) are the major cause of mortality worldwide. According to WHO, 17.9 million people died from CVDs in 2019, accounting for 32% of all global fatalities.
Though CVDs cannot be treated, predicting the risk of the disease and taking the necessary precautions and medications can help to avoid severe symptoms and, in some cases, even death.
As a result, it is critical that we accurately predict the risk of heart disease in order to avert as many fatalities as possible.

**Acknowledgements**
* <a href="https://my.clevelandclinic.org/health/diseases/21493-cardiovascular-disease">Detailed overview of disease</a>
* <a href="https://grow.almabetter.com/data-science/home">about company</a>

**Features**
* I did some data wrangling and  data manipulations.
* Data visualizaion, storytelling and experimenting with charts.
   - Number of paitents who having TenYearCHD or not.
   - Number of people who smoke or dont smoke.
   - people with Blood pressure problem.
   - Number of deabetic petients who have glucose level greater than 125 and also have TenYearCHD.
   - Number of CHD patients who are in danger due to heartRate.
   - CORRELATION heatmap.
   - Pair plot.
* Hypothesis Testing
   - Normality test
   - Variable dependency test
   - Check whether discrete variable are related.
* Feature selection by
   - Random forest Importence
   - Wrapper methods
   - Information gain
* Many continous variable are skewed. By log transformation, i aim to reduce the magnitude of skew in these variable to a certain extent.
* I used SMOTETomek for data balancing.
* ML model implementaions
   - KNeighborsClassifier
   - RandomForestClassifier
   - DecisionTreeClassifier
* I have used GridSearchCV hyperparameter optemization technique.
* I used ROC curve(Receiver Operating characteristic curve) for showing performance of classification model.
* Confusion metrics as Evaluation metrics.
* I exlained the model by using SHAP.
* RandomForestClassifier algorithm is the best with a 0.82 AUC score.

***Classification report***

<img src="https://drive.google.com/uc?export=view&id=1ln7oeCiZS_x2dq40hTV_9ODUtwyJj8It" alt="Image Description" width="600" height="300">


***Contributors***
SAMEER KHAN

 
