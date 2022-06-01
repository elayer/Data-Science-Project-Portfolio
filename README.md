# Data Science Project Portfolio
Welcome to my project portfolio! Click on any of the project titles to go to an individual project's repository.

# [Project 1) Carvana Cars Regression Project:](https://github.com/elayer/CarvanaCarsProject)
* Created a model base to help those considering selling or trading in their car to Carvana get an idea of what price they can expect.

* Scraped roughly two thousand pages of car data from Carvana's used car listings using a custom-built web scraper. 

* Cleaned and processed the data for preparation for EDA and model building tasks. Tasks ranged from imputing missing values to feature engineering new versions of variables which had high cardinality. I also performed some outlier detections techniques using PyCaret as well as Z-score.

* Within Model Building, I began by dropping insignificant attributes as well as variables exhibiting multicollinearity. After using the OLS method from statsmodels, I moved into applying linear regression techniques such as standard Linear Regression, Elastic Net, and Kernel Ridge. I followed this up by applying more powerful models such as Random Forest, LightGBM, and XGBoost regression.

![](https://github.com/elayer/elayer.github.io/blob/main/images/geomap_prices.png "Average Price per State Map")

# [Project 2) Amazon Gaming Computer Price Estimator:](https://github.com/elayer/Amazon-Computer-Project)

* Created a model to help those looking to buy a gaming computer from Amazon make a more informed decision based on the specs of a computer.

* Scraped roughly 200 pages of gaming desktop product listing information from Amazon with a custom-built web scraper. 

* Engineered a few features based on the product information included in the title of a product listing. Such as features for liquid cooling and bluetooth capability.

* Began model building with Linear, Lasso, Ridge, and ElasticNet linear models, as well Random Forest regression. Then, built optimized models using Optuna with XGBoost and CatBoost regression.

* Created an API for potential clients using Flask with functional HTML pages for local use. 

![](https://github.com/elayer/elayer.github.io/blob/main/images/price-by-processor-type.png "Price by Processor Type")

# [Project 3) Fetal Health Condition Classifier:](https://github.com/elayer/Fetal-Health-Classifier-Project)

* Created a model to classify for babies in fetal development, cardiotocography exams on whether the fetus has normal health conditions, is suspect of having some pathology, or has some pathological condition.  

* Engineered new features utilizing Linear Discriminant Analysis and KMeans Clustering. I also performed PCA to orchestrate further and visualize further class separability.

* Began model building with Support Vector Machine, K-Nearest Neighbors, Logistic Regression, Random Forest Classifier, and AdaBoost Classifier. I then used optuna for hyperparameter optmimization with XGBoost Classifier and CatBoost Classifier.

* Created an API for potential clients using Flask with functional HTML pages for local use.

![](https://github.com/elayer/elayer.github.io/blob/main/images/fetal_homepage.png "Fetal Health Classifier Homepage")
