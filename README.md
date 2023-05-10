 # Employee-Performance-Management-System

The data is supervised and categorical.

The predictor variables are ordinal and a few among them are nominal. The target variable 'Performance Rating' is ordinal.

To analyze the data, various data processing techniques like Label Encoding and Standardization is used. Correlation Coeffecient is used to interpret the relationship between variables. The most important features selected are Department, Job Role, Environment Satisfaction, Last Salary Hike Percent, Work Life Balance.

For training the data and predicting the target, algorithms used are Logistic Regression, Support Vector Machine, Naive Bayes, and K-Nearest Neighbor.

A separate analysis of Department wise Performance is to be carried out. Data Analysis Summary.

# Summary -

The project is to be done with the purpose of finding out factors which affect the Performance of the employees, training a model which accurately predicts the Performance Rating of the employee, analyzing the data to provide recommendations to improve the performance and gain insights from the analysis.

The following steps are needed to be carried out:

(a) Import the data provided, find out the predictor & target variables and look for missing values.

(b) Analysis of Department wise performance as asked.

(c) The Top 3 important features affecting the employee performance.

(d) Label Encoding the ordinal columns.

(e) Calculate correlation coefficient to find out the relationship between variables and then select the important features for analysis.

(f) Standardizing the data and splitting it into test and train.

(g) Training the data using algorithms like Logistic Regression, Support Vector Machine, Naive Bayes, K-Nearest Neighbour and checking the accuracy to find out which algorithm is the best.

(h) Exporting the model with highest accuracy.


# Results

1) We don't have any missing and duplicate values is the dataset.

### __2) Goal 1 :-__  

From the above graph we can conclude that from the EmpDepartment Development department is showing High performance rating

Sales: The Performace rating level 3 is more in the sales department. The male performance rating the little bit higher compared to female.

Human Resources: The majority of the employees lying under the level 3 performance . The older people are performing low in this department. The female employees in HR department doing really well in their performance.

Development: The maximum number of employees are level 3 performers. Employees of all age are performing at the level of 3 only. The gender-based performance is nearly same for both.

Data Science: The highest average of level 3 performance is in data science department. Data science is the only department where less number of level 2 performers. The overall performance is higher compared to all departments. Male employees are doing good in this department.

Research & Development: The age factor is not deviating from the level of performance here where different employees with different age are there in every level of performance. The R&D has the good female employees in their performance.

Finance: The finance department performance is exponentially decreasing when age increases. The male employees are doing good. The experience factor is inversely relating to the performance level.

### __3) Goal 2:-__

***i)Employee Enviroment satisfaction:***

Maximum Number of Employees Performance Rating belongs to EmpEnvironmentSatisfaction Level 3 & Level 4, It contains 367 & 361.

***2)Employee last salary hike percent:***

More Number of Employees whose salary hike percentage belongs to 11-19 % are getting 2 & 3 performance rating Maximum time. Employees whose salary hike percentage is in between 20-22%, There performance rating is 4

***3)Employee work life balance:***

In EmpWorkLifeBalance, level 3 is showing high Performance Rating of employees.

### __4) Goal 4:-__

The trained model is created using the machine learning algorithm as follows with the accuracy score

i) Logistics Regression: 83.33% accuracy

ii) K-nearest Neighbour: 83.33% accuracy

iii) Support vector Machine : 84.40% accuracy

iv) Naive Bayes Bernoulli : 79.44% accuracy

__The Maximum accuracy score is support vector machine is 84.40%__

5) The goal is to export the model with the highest accuracy to make accurate predictions for new employee performance data and provide recommendations to improve employee performance based on insights gained from the analysis.
