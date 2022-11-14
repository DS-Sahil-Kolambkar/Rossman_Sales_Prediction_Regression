# Rossman_Sales_Prediction_Regression

# Problem Description
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.
You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

# **Steps Performed In This ML(Supervised) Project**
---

Handling dataset with the fundamental steps to unvail the factors :

* Importing Libraries And Loading The Datasets
* Overview Of The Datasets 
    *   Reading & Inspection Of First Dataset
    *   Reading & Inspection Of Second Dataset
    *   Merging both the datasets
    *   Further analysing both the datasets
* Data Wrangling And Processing
    *   Converting Dtype Of Feature
    *   Extracting Date
    *   Combining And Creating Columns
    *   Null Value Treatment
    *   Handling Outliers
* Exploratory Data Analysis
* Key Findings From EDA
* Feature Engineering 
    *   Feature Selection
    *   Multicollinearity
    *   Dependent Variable Transformation
    *   Scaling Numberical Features
    *   Dummification
* ML Model
    *   Train-Test Split
    *   Model Training And Prediction
  * Linear Regression
  * Lasso Regression
  * Ridge Regression
  * Decision Tree Regression
  * Random Forest Regression
  * Gradient Boosting Regression
  * XGboost Regression
    * Feature Importance
* HyperParameter Tuning
* Feature Importance of Best performing Model
* Cross Validating for Hyperparameter Tuned Best Performing model
* Key Findings from Machine Learning
* Conclusions 

# **7. Conclusions**

---


1. Store model 'b' have least number of stores in Rossmann yet it performed well and made more sales than other store models so it is advisable to increase the number of 'b' store model. 

2. Assortment level 'Basic' have the maximum number of stores in Rossmann yet it performed very badly but at the same time 'Extra' and 'Extended' assortment level with less number of store had preformed extra ordinarily so it would be advisable to increase these assortment level.

3. Linear relationship have been found among customer, sales and promo.And it has been seen that most of the customers came for shopping during the promo days as the cost was lower on those days. So promo should be initiated to more stores to increase the sales.

4. Sales has been low on the initial days of the month as compared to the end days, it can be assumed that people used to shop for the next month at the end of the previous month. Those products can be mainly be of basic necessities of a person's daily life.

5. Average sales on weekdays was more as compared to weekends because  promo's were provided to the customers during weekdays to increse the sales and not to weekends and reason might be that store use to remain close on Sundays.

6. Sales during November and December month was more high compared to other months and that can be due to festive season in western European countries.

7. Mostly competitor stores weren't that far and the stores were densely located near each other and also sales were higher when competition was nearer. So when competition was not there and sales were also low that might be because of the location factor like rural area.

7. School holidays also influence the sales a lot as it can be observed that 17.8% of the sales gets affected by the school holidays which also means that around 17% of the sales are oriented from the school students. 

8. XGBoost was the best performing model(Adjusted R2 :0.993358) even though it was one of the slowest from our machine learning analysis.

9. According to cross validate method of sklearn while cross validating 3 times our XGboost regression model had following performance :

  Average fit_time is 36.33202

  Average score_time is 0.152

  Average R2 score is 0.99353
