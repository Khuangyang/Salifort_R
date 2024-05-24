# Salifort Motor
To improve employees rentation rate.

# Overview 
Salifort Motors seeks to improve employee retention and seeking to answer What’s likely to make the employee leave the company?

​
# Business Understanding 
This model helps predict whether an employee will leave and identify which factors are most influential. 
These insights can help HR make decisions to improve employee retention.

# Data Understanding
Since the variable we are seeking to predict is categorical, the team could build either a logistic regression or a tree-based machine learning model.
The random forest model slightly outperforms the decision tree model.
 

# Modeling and Evaluation 
Logistic Regression The logistic regression model achieved precision of 80%, recall of 83%, f1-score of 80% (all weighted averages), and accuracy of 83%, on the test set.tree model After conducting feature engineering, the decision tree model achieved AUC of 95.8%, precision of 85.7%, recall of 90.4%, f1-score of 87.9%, and accuracy of 95.8%, on the test set. The random forest modestly outperformed the decision tree model. In the random forest model,last_evaluation, tenure,number_project, overworked and salary have the highest importance. These variables are most helpful in predicting the outcome variable, left.

![Feature Importance](https://github.com/Khuangyang/Salifort-Motor/blob/main/salifort_rf2_importance.png)
Horizontal bar chart showing feature importance of random forest model.

# Conclusion
The models and the feature importances extracted from the models confirm that employees at the company are overworked.In order to retain employees, company can cap the number of projects that employees can work on. Consider promoting employees who have been with the company for atleast four years, or conduct further investigation about why four-year tenured employees are so dissatisfied. Either reward employees for working longer hours, or don't require them to do so. If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear. Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts. High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort
