This assignment utilizes sklearn ensemble techniques such as Bagging Classifier, Random Forest Classifier, AdaBoost Classifier and Gradient Boosting Classifier and XGB Classifier from xgboost library to build machine learning based solution that: -

•	Facilitate the process of visa approvals.

•	Recommend a suitable profile for the applicants for whom the visa should be certified or denied based on the drivers that significantly influence the case status.

Model selection

Reducing false positive was key since this will lead to bringing on board employees that could be found locally denying locals opportunity. XGBoost model trained with under sampled data was the best model with precision of 90.01% hence selected for the assignment 

Key Insights from the model

•	From EDA factors that have impact on certification status that they should pay closer look into are education of employees, continent, job experience, prevailing wage, employer number of employees and unit of wage.

•	From the predictive model, factors that they should pay closer look into: - 
* Education of employees with those with high school having upper hand in certification, followed by masters, doctorate in that order.
 * Employees with experience 
* Unit of wage being year 
* Continent with Europe having upper hand followed by North America, Asia and south America in that order,
* Prevailing wage 
* Region of employment with Midwest, west, Northeast, south having upper hand in that order
 * Nature of position with full time 
* Year of establishment
* No of employees

Learnings:

I gained hands-on experience in end-to-end machine learning workflows including exploratory data analysis, rigorous data pre-processing, and implementing advanced ensemble models such as Bagging Classifier, Random Forest Classifier, AdaBoost Classifier, Gradient Boosting Classifier and XGB Classifier. I also learned to optimize model performance through hyperparameter tuning and extract actionable business insights. This project enhanced my ability to identify key factors influencing visa outcomes and recommend data-driven decisions for applicant approval or denial.

