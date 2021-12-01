##### Compilation of Python programming code of various Data Science projects using Supervised Machine Learning models - Linear Regression, Logistic Regression, Decision Tree, Random forest, Bagging Classifier, AdaBoost, Gradient Boosting and XGBoost. 
| Project                          |Description                                       |Jupyter Notebook Link     
:-----------------------------------:|:--------------------------------------------------|:--------------------
| Cardio Fitness Product Analysis  | <p>* Through **Statistical analysis** using Python Libraries _Numpy and Pandas_, analyzed which of the various cardio fitness products is effective in terms of fitness and usage.</p> <p>* Performed Exploratory Data Analysis (EDA) through **data visualization** (univariate and multi-variate analysis) using Python Library _Seaborn_, to draw relationship patterns and correlation between features to build customer profile of the different fitness products. Generated a set of insights & recommendations that will help the company in targeting new customers.</p>| https://github.com/sandhyakaranam/Data-Science-Projects/blob/main/Cardio%20Good%20Fitness-EDA.ipynb    |
| Cars4U - Tech start-up that aims to find foothold in the used car market     | <p>* Built a **Linear Regression** predictive model with SciKit-Learn, that can effectively predict within ~13% of the used car price (using metric _MAPE_) and can explain variance in the used car price up to 94% (using metric _R-squared_). </p> <p>* From the baseline model, improved complexity of the model by reducing to one third of the features using _Sequential Feature Selector_ (SFS) and obtained similar model performance, that can effectively predict within ~14% of the used car price and can explain variance in the used car price up to 90%. </p> <p>* Through EDA, generated insights and recommendations, to help business in devising profitable strategies using differential pricing.</p> | https://github.com/sandhyakaranam/Data-Science-Projects/blob/main/SLR_Cars4U%20Pricing%20Model.ipynb      |
| AllLifeBank Personal Loan Campaign Modelling     |  <p>* Built **Logistic Regression and Decision Tree** predictive models, that the bank can deploy to identify potential customers who will be interested in taking a personal loan and that the bank can use to find the key factors that will have an impact on a customer taking a personal loan or not.</p> <p>* Built Logistic Regression model with optimal threshold using _AUC-ROC curve_ that gave a  _recall_ of 0.85 on Test data. Also, built this model with optimal threshold using _Precision-Recall curve_, that will help the bank to maintain a balance in identifying potential customer and the cost of resources, with _F1-score_ of 0.75 on Test data. </p> <p>* Built **Decision Tree** default model and tried hyper tuning the model using _Pre-pruning_ and _Cost complexity pruning_. On this dataset, although the tree became much simpler and readble with pruning, Decision Tree default model gave best performance compared to hyper tuned models. </p> <p>* Overall, on this dataset, Decision Tree model gives best recall of 0.93 on the test data, compared to Logistic Regression model </p> <p>* Looking at important variables based on _p-values_ in Logistic regression and Feature importance in Visualized Decision trees, found the key factors that have an impact on Personal Loan.</p> | https://github.com/sandhyakaranam/Data-Science-Projects/blob/main/SLC_LR_DT%20-%20Bank%20Personal%20Loan%20Campaign.ipynb       |
| Credit Card Churn Prediction        | <p>* Analyzed data through **Statistical Analysis** and **Exploratory data Analysis** to draw relationship patterns and correlation between variables to draw insights. </p> <p>* Split the dataset into train, Validation and test sets and performed _Feature Engineering_ on Train and Validation data like missing value imputation using _SimpleImputer_ and encoding categorical variables using _one-hot encoder_. </p> <p>* Built and Trained different classification models: **Logistic Regression, Bagging Classifier, Random Forest, Gradient Boosting, AdaBoost, XGBoost and Decision Tree** with original data, over sampled  data (using _SMOTE_) and under sampled data (using _RandomUnderSampler_).</p> <p>* Analyzed all 6 models prediction accuracy using _K-Fold cross-validation score_ and _recall_ score and picked the 3 best performance models : Gradient Boosting, AdaBoost and XGBoost with original and under sampled data. </p> <p>* Hyper Tuned these 3 best models with under sampled data and original data and compared the model performance. Gradient Boosting with original data gave more generalized performance on test data. </p> <p>* Built the final **Pipeline** model with the best parameters obtained for Gradient Boosting classification model that the bank can deploy to identify customers who are at the risk of Attrition.</p> | https://github.com/sandhyakaranam/Data-Science-Projects/blob/main/Hyper%20Tuning%20and%20Pipeline%20-%20Credit%20Card%20Churn%20Prediction.ipynb        |
