### SyriaTel-Customer-Churn-Project.
The SyriaTel Customer Churn Project.

## OVERVIEW
This project is about a telecommunication company called SyriaTel that needs to understand their churn rate(which is a measure of a company's  loss of subscribers for a given period of time/opposite for growth rate)
It is calculated by : 
(Customers at the beginning of period-Customers at the end pf period)/Customers at the beginning of the period.
Churn number is the number of customers who end their relationship with a company within a given period.
Calculating the churn rate is so important for various reasons.
- Essential for tracking
- For monitoring purposes
- Optimizes for sustainable growth
## BUSINESS AND DATA UNDERSTANDING
### main objective
- Predict whether a customer will ('soon') stop doing business with SyriaTel telecommunication Company
####  Specific objectives
- 
-
## DATA UNDERSTANDING
The data contains the following variables.
- state, string. 2-letter code of the US state of customer residence
- account_length, numerical. Number of months the customer has been with the current SyriaTel communications
- area_code, string="area_code_AAA" where AAA = 3 digit area code.
- international_plan, (yes/no). The customer has international plan.
- voice_mail_plan, (yes/no). The customer has voice mail plan.
- number_vmail_messages, numerical. Number of voice-mail messages.
- total_day_minutes, numerical. Total minutes of day calls.
- total_day_calls, numerical. Total number of day calls.
- total_day_charge, numerical. Total charge of day calls.
- total_eve_minutes, numerical. Total minutes of evening calls.
- total_eve_calls, numerical. Total number of evening calls.
- total_eve_charge, numerical. Total charge of evening calls.
- total_night_minutes, numerical. Total minutes of night calls.
- total_night_calls, numerical. Total number of night calls.
- total_night_charge, numerical. Total charge of night calls.
- total_intl_minutes, numerical. Total minutes of international calls.
- total_intl_calls, numerical. Total number of international calls.
- total_intl_charge, numerical. Total charge of international calls
- number_customer_service_calls, numerical. Number of calls to customer service
- churn, (yes/no). Customer churn - target variable.
## MODELLING
I used 2 models
- Logistic Regression- ensembled
- Decision Tree
Logistic Regression ensembled - I got an accuracy score of 0.857, thus Logistic Regression model is good for predicting the churn rate
Decision Tree
The decision tree is a non-parametric method, which does not depend upon probability distribution assumptions and can handle high-dimensional data with good accuracy.
Here I found an accuracy of 0.857.
## EVALUATION
Logistic regression and Decision Tree accuracy score value of 0.857 signifies that the model is appropiate due to the high score.From the confusion matrix we also see that there are 857 correct predictions while 143 incorrect predictions.Thus we can conclude that Decision Tree Classifier made a good prediction. 
The two models are fit for predicting the  churn rate due to a high percentage accuracy.
The f1_score had a value of 0.4615
The recall value was 0.4285
## CONCLUSION
I can conlude that a decision tree model is fit for for modelling our data.
The two models are fit for predicting the  churn rate due to a high percentage accuracy.