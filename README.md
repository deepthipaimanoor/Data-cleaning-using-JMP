Data Cleaning with JMP

Description:

The project's objective is to develop a prediction model utilizing the SEMMA technique and determine if a patient who has a myocardial infraction will subsequently develop chronic heart failure. The dataset contains information about the patient 
(i) at the time of admission and 
(ii) on the third day of the hospital period during the treatment of myocardial infraction. One of the most difficult issues in contemporary medicine is Myocardial Infraction. In the first year following an acute myocardial infarction, mortality rates are very high. 

The nominal variable "Chronic Heart Failure" is the goal variable in this data collection. As a result of a Myocardial Infraction complication, this will demonstrate whether the patient has experienced persistent heart failure.


Installation:

To run this project on your machine you need to install any JMP application on windows


Data Exploration:

In the given database, we can see 124 columns and 1699 rows. Patients' independent statistics, their state at the time of admission, and their medical history are represented.
The nominal variable "Chronic Heart Failure" is the goal variable in this data collection.This will reveal whether the patient has encountered chronic heart failure.

Variables :

Out of 124 columns, based on the definitions and theoretical knowledge, 20 variables were shortlisted to pre-process further.

<img width="911" alt="Screenshot 2024-01-29 at 7 13 09 PM" src="https://github.com/deepthipaimanoor/Data-cleaning-using-JMP/assets/155695373/493eca07-5439-448f-9b2b-4c0b6f85e4e8">



Modification:

Following pre-processing steps were followed: 
1. Removed Missing Values: The data value "?" is mentioned in the columns.A total of 462 rows are missing from the data set when these are taken into account as missing values.
2. Outliers: There were no outliers in the dataset because most of the values were nominal.
The Time elapsed from the beginning of the attack of CHD to the hospital has been converted from continuous to categorical as per the definition.
3. Only 20 of the 124 columns were taken into consideration for evaluation since, they either contain nearly constant values, a significant number of missing values, or no strong correlation with the target variable in accordance with the data on the website.
4. As there was no much co-relation between the variables, I have not taken any Principal Components for analysis. Rather worked on important variables as inputs.

Conclusion:

The main factors that influence whether persistent heart failure develops as a side effect of myocardial infarction are age, gender, and past medical records.
--If atrial fibrillation is seen on the ECG at the time of hospital admission and there is a family history of chronic heart failure, there is a very high likelihood that the patient will develop chronic heart failure.
--Therefore, older patients with already-evaluated medical issues such as diabetes, heart-related history, or chronic bronchitis should receive more precise care and should not hesitate in rushing to the hospital..
