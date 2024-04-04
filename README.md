Project proposal to predict credit card approval


Section 1: Questions to Answer

What questions do you want to answer? 2-5

Why is your proposal important in today’s world? How predicting a good client is worthy for a bank?  

How is it going to impact the banking sector? 

If any, what is the gap in the knowledge or how your proposed method can be helpful if required in future for any bank in India.


Section 2: Initial Hypothesis (or hypotheses)

Here you have to make some assumptions based on the questions you want to address based on the DA track or ML track. 

If DA track please aim to identify patterns in the data and important features that may impact a ML model.

If ML track please perform part ‘i’ as well as multiple machine learning models, perform all required steps to check if there is any assumption and justify your model. Why is your model better than any other possible model? Please justify it by relevant cost functions and if possible by any graph.

From step 1, you may see some relationship that you want to explore and will develop a belief about data


Section 3: Data analysis approach

What approach are you going to take in order to prove or disprove your hypothesis?

What feature engineering techniques will be relevant to your project?

Please justify your data analysis approach.

Identify important patterns in your data using the EDA approach to justify your findings.


Section 4: Machine learning approach

What method will you use for machine learning based predictions for credit card approval?

Please justify the most appropriate model.

Please perform necessary steps required to improve the accuracy of your model.

Please compare all models (at least 4  models).


Utilize machine learning approaches to predict credit card approval based on customer information.


A bank's credit card department is one of the top adopters of data science. A top focus for the bank has always been acquiring new credit card customers. Giving out credit cards without doing proper research or evaluating applicants' creditworthiness is quite risky. The credit card department has been using a data-driven system for credit assessment called Credit Scoring for many years, and the model is known as an application scorecard. A credit card application's cutoff value is determined using the application scorecard, which also aids in estimating the applicant's level of risk. This decision is made based on strategic priority at a given time.


Customers must fill out a form, either physically or online, to apply for a credit card. The application data is used to evaluate the applicant's creditworthiness. The decision is made using the application data in addition to the Credit Bureau Score, such as the FICO Score in the US or the CIBIL Score in India, and other internal information on the applicants. Additionally, the banks are rapidly taking a lot of outside data into account to enhance the caliber of credit judgements.


Features name: (Credit_Card.csv)

Ind_ID: Client ID

Gender: Gender information

Car_owner: Having car or not

Propert_owner: Having property or not

Children: Count of children

Annual_income: Annual income

Type_Income: Income type

Education: Education level

Marital_status: Marital_status

Housing_type: Living style

Birthday_count: Use backward count from current day (0), -1 means yesterday.

Employed_days: Start date of employment. Use backward count from current day (0). Positive value means, individual is currently unemployed.

Mobile_phone: Any mobile phone

Work_phone: Any work phone

Phone: Any phone number

EMAIL_ID: Any email ID

Type_Occupation: Occupation

Family_Members: Family size


Another data set (Credit_card_label.csv) contains two key pieces of information

ID: The joining key between application data and credit status data, same is Ind_ID

Label: 0 is application approved and 1 is application rejected. 



SQL

Use MySQL or PyMySQL to perform the below queries. 

Note: Use only the cleaned data for SQL part of the project


Group the customers based on their income type and find the average of their annual income.

Find the female owners of cars and property.

Find the male customers who are staying with their families.

Please list the top five people having the highest income.

How many married people are having bad credit?

What is the highest education level and what is the total count?

Between married males and females, who is having more bad credit? 
