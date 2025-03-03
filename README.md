# Providing-data-driven-suggestions-for-HR
## Overview 
The goal of this project was to predict if an employee will leave based on data given by a survey taken from the HR department of a motors company. the logistic regressing yielded precision of 80%, recall of 83%, f1-score of 80% (all weighted averages), and accuracy of 83%, on the test set. And the tree-based ML, After conducting feature engineering, the decision tree model achieved AUC of 93.8%, precision of 87.0%, recall of 90.4%, f1-score of 88.7%, and accuracy of 96.2%, on the test set. The random forest modestly outperformed the decision tree model. 

## Business Understanding
The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company. They collected data from employees, but now they don’t know what to do with it. They refer to you as a data analytics professional and ask you to provide data-driven suggestions based on your understanding of the data. They have the following question: what’s likely to make the employee leave the company?

## Data
The data consists of 14k employee survey results from the HR department. The data consists of satisfaction level, department, salary level, projects completed, years spent at the company, if they left the company, average monthly hours worked, and other columns. The scatterplot below shows Jest a brief correlation between two variables that are most important in developing the model.
![my_hr_scatterplot](https://github.com/user-attachments/assets/66896cdc-0d69-4304-9a30-250b356bb762)

## Modeling 
The logistic regression model achieved precision of 80%, recall of 83%, f1-score of 80% (all weighted averages), and accuracy of 83%, on the test set. I wanted a model that yielded a better result so I tried a tree based model, both a decision tree and random forest. The decision tree model yielded AUC of 93.8%, precision of 87.0%, recall of 90.4%, f1-score of 88.7%, and accuracy of 96.2%, on the test set. The random forest slightly outperformed the decision tree model.

![my_hr_dtreeFE](https://github.com/user-attachments/assets/2e74ce1c-ab80-4d96-8573-53639afae979)
![my_hr_RF_FI](https://github.com/user-attachments/assets/436b8cc0-b0f9-47ca-b66d-ea5193b27318)


## Conclusion
The models and the feature importances extracted from the models confirm that employees at the company are overworked.

To retain employees, the following recommendations could be presented to the stakeholders:

 - Cap the number of projects that employees can work on.
 - Consider promoting employees who have been with the company for atleast four years, or conduct further investigation about why four-year tenured employees are so       dissatisfied.
 - Either reward employees for working longer hours, or don't require them to do so.
 - If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit,        make them clear.
 - Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts.
 - High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute        more/put in more effort.
