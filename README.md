# Bank Customer Churn model with Explainable-AI

When customers or subscribers stop doing business with a company or service, it is known as customer churn. The goal of this project is to identify potential telecom business clients and analyze their reasons for leaving using LIME. Local Interpretable Model-agnostic Explanations is the acronym for LIME. LIME focuses on developing neighborhood surrogate models to justify specific forecasts.

## Features
     
 1.   Geography         
 2.   Gender           
 3.   Age                
 4.   Tenure            
 5.   Balance          
 6.   NumOfProducts      
 7.   HasCrCard          
 8.   IsActiveMember     
 9.   EstimatedSalary  
 10.  Exited  
 11.  CreditScore    
## EDA

1. Data set is extremely imbalanced.

2. Customers from France are least likely to leave while the probability of customes leaving is most for Germany.

3. Females are most likely to leave the bank.

4. Customers using 3 or more products are most likely to leave. All customes using all 4 products left.

5. The customers with credit card are less likely to leave.

6. The exit of a customer is related with Age,Balance and if the customer is an active member.

7. There seems to be an overlap between all points so linear prediction methods are to be avoided.
## Feature Importance

The most important features:

1. Age 
2. IsActiveMember
3. NumOfProducts
4. Gender_Male
5. CreditScore
6. EstimatedSalary
7. Tenure
8. Geography_Spain
9. HasCrCard
10. Geography_Germany
