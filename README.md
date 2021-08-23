# Health-insurance-cross-sell-prediction

Predict Health Insurance Owners' who will be interested in Vehicle Insurance**

Your client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the customers from past year will also be interested in Vehicle Insurance provided by the company.


feature

1 id|int64|Person id

2 Gender |object|ttype of Gender(male,female)

3 Age|int64|Person age

4 Driving_License |int64|Driving lisence have or not

5 Region_Code|float64|code region

6 Previously_Insured|int64|Previously insured or not

7 Vehicle_Age|object|vehicle of the age(1-2 years,>2 year,<1year)

8 Vehicle_Damage|object|Vehicle damage('no' 'yes')

9 Annual_Premium|int64|premium amount

10 Policy_Sales_Channel|float64|Policy

11 Vintage|int64|Quality of vehicle
Label

 12 Response|int64|Response(0,1)

Data Analysis

1 Find Unwanted Columns

2 Find Missing Values

3 Find Features with one value

4 Explore the Categorical Features

5 Find Categorical Feature Distribution

6 Relationship between Categorical Features and Label

7 Explore the Numerical Features

8 Find Discrete Numerical Features

9 Relation between Discrete numerical Features and Labels

10 Find Continous Numerical Features

11 Distribution of Continous Numerical Features

12 Relation between Continous numerical Features and Labels

13 Logistic regression,Random forest,XGboost

Feature Engingineering

Drop unwanted features

Handle missing value

Handle categorical features

Handle feature scaling

As Per DataAnalysis

no missing value found

no feature found with one value

3 categorical features

id,"Vintage", "Vehicle_Age", "Policy_Sales_Channel","Previously_Insured","Driving_License" are dropped

Conclusion

1 Customers of age between 30 to 60 are more likely to buy insurance.

2 Customers with Driving License have higher chance of buying Insurance.

3 Customers with Vehicle_Damage are likely to buy insurance.

4  The variable such as Age, Previously_insured,Annual_premium  are more afecting the target variable.

5 comparing ROC curve we can see that Random Forest model preform better. Because curves closer to the top-left corner, it indicate a better performance.
