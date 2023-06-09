# deep-learning-challenge

Report:
The purpose of this analysis was to use a machine learning model to predict  whether applicants will be sucessful in obtaining funding. A CSV containing over 34,000 organizations was used and the dataset contained column data such as:
EIN and NAME
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS
ASK_AMT
IS_SUCCESSFUL

Data Preprocessing:
Target Variables consisted of: IS_SUCCESSFUL
Feature VARIABLES: APPLICATION_TYPE, AFFILIATION,CLASSIFICATION,USE_CASE,ORGANIZATION,STATUS,INCOME_AMT,SPECIAL_CONSIDERATIONS,ASK_AMT
The varibales that should be removed are ORganization ID, EIN, and NAME

COMPILING, TRAINING, AND EVALUATING THE MODEL
1st attempt: 
Neurons: 10,20
Layers: 2

2nd attempt:
Neurons:80,60
Layers:2

3rd attempt:
Neurons: 300,150
Layers: 2

My attempt to increase the accuracy to 75% was to increase the amount of Neurons being used. This did not work.
I was unsuccessful at achieving a 75% binary_accuracy.

Summary:
