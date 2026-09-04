# Insurance-cross-selling
Data Science Master’s: Fundamentals of Machine Learning module project.

AssurePredict is a leading insurance company, specializing in offering innovative risk management solutions. This project aims to build a predictive model capable of identifying potential cross-selling opportunities for existing customers, by identifying those who might be interested in purchasing an additional policy for their vehicle.  

## Objective
The goal is to develop a machine learning model that predicts whether customers who currently hold health insurance might be interested in taking out a vehicle insurance policy.  
The model will help AssurePredict improve the effectiveness of its cross-selling strategies and increase market penetration.

## Dataset
The dataset contains detailed information about customers and their insurance-related behavior. The main features of the dataset are:  

- id: unique customer identifier  
- Gender: customer's gender  
- Age: customer's age
- Driving_License: 1 if the customer holds a driving license, 0 otherwise
-	Region_Code: unique code of the customer's region of residence
-	Previously_Insured: 1 if the customer already has an insured vehicle, 0 otherwise
-	Vehicle_Age: age of the customer's vehicle
-	Vehicle_Damage: 1 if the customer has had accidents or vehicle damage in the past, 0 otherwise
-	Annual_Premium: annual amount of the insurance premium paid by the customer
-	PolicySalesChannel: channel used to sell the policy (e.g. email, phone, in person)
-	Vintage: number of days the customer has been insured with AssurePredict
-	Response: 1 if the customer accepted the cross-sell offer, 0 otherwise.

