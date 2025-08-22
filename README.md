# ML-in-HR-analytics
This project includes a creation of a ML model used for HR analytics for some Sales Company. 
HR analytics helps businesses optimize their HR management: businesses provide data, and analysts suggest ways to avoid financial losses and employee attrition, which may lead to losing people that bring money to the company. Machine learning can be used by HR analysts to answer business questions more quickly and accurately.
The Sales Company kindly provided me data on the characteristics of its employees. This includes the employee's level of satisfaction with their work at the company. This information was obtained through feedback forms, where employees fill out a questionnaire and their level of satisfaction is calculated on a scale from 0 to 1, with 0 representing complete dissatisfaction, and 1 representing complete satisfaction. 
During my work on the project several tasks were solved. Data were analyzed for completeness and checked for anomalies (outliers, crazy values and errors). Remember, if data are garbage, no magical AI will help. After data checkup, two models were built. 
The first model predicts employee satisfaction based on customer data: 
•	id — unique employee ID;
•	dept — the department where the employee works;
•	level — level of the position held;
•	workload — employee's workload level;
•	employment_years — length of time worked for the company (in years);
•	last_year_promo — shows whether there has been an increase in the last year;
•	last_year_violations — shows whether an employee has violated an employment contract in the last year;
•	supervisor_evaluation — the employee's supervisor's assessment of the employee's performance;
•	salary — monthly salary of the employee;
•	job_satisfaction_rate — the employee's level of satisfaction with their work in the company, the target feature.
The second model can predict whether an employee will leave the company using the same input features as for the first model (job satisfaction prediction) including job satisfaction rate.
Project contains data analysis, model creation, testing and validation.
Conclusions are made in the end.
