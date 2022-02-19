# Sales-Lead-project
***Sales - Lead Effectiveness***

**Business Case:  
  
FicZon Inc is an IT solution provider with products ranging from on premises products to SAS based solutions. FicZon major leads  generation channel is digital and through their website.  
FicZon business is majorly dependent on the sales force  effectiveness. As the market is maturing and more new competitors  entering the market, FicZon is experiencing the dip in sales.  
Effective sales is dependent on lead quality and as of now, this is  based on manual categorization and highly depended on sales staff.  Though there is a quality process, which continuously updates the  lead categorization, it’s value is in for post analysis, rather than  conversation. 
FicZon wants to explore Machine Learning to pre-categorize the lead  quality and as result, expecting significant increase in sales  effectiveness. 

**PROJECT GOAL: 
1. Data exploration insights – Sales effectiveness. 
2. ML model to predict the Lead Category.


**********************************************

***Status mapping – Lead Qualification Process
• Open 
• Just Enquiry ,Qualified Lead 
• Long term  Lead 
• Not  Responding, Opportunity 
• In Progress – Negative 
• In progress - Positive  
• Potential 
• Junk Lead Business 
• Lost 
• CONVERTED 
• Converted


***Objective***
✔ Classify Leads as  
✔ Not Potential(0) / Potential(1) / Not sure(2) 
✔ Rationalize the lead statuses to a few logical number ✔ Key: choosing the right set of rows for the model 
✔ Approach 1: Use Test Data and optimize for recall. Interpret  confusion matrix as follow: 
✔ TP = Potential 
✔ TN = Not Potential 
✔ FN+FP = Not sure
✔ Approach 2: Use test data 
✔ Iteration 1 Prediction: Same as model in Approach1 ✔ TP = Potential 
✔ Iteration 2: Boost with Model2 with FN+TN+FP records of  test data from iteration1. Optimize with high precision.  Interpret Confusion report of this as below 
✔ TN = Not potential 
✔ TP+FN+FP = Not sure 
✔ Iteration 2 helps in reinforcing the TN = Not potential  outcome from Iteration1.
 

***Explain Coding / outcomes 
✔ Show using Jupyter



