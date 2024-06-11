# ETL_Informtica_Power_Center
# Overview
This Informatica project involves extracting, transforming, and loading (ETL) data from two CSV files: Churn_Modelling2.csv and Churn_Modelling3.csv. The objective is to perform various analyses of the data and generate specific outputs as outlined below. The project also includes extracting data from the Oracle HR schema, performing transformations, and loading the transformed data back into the database

# Tasks
1. Sum of Balances for Male and Female Customers:
 - Calculate the sum of balances for male and female customers.
2. Number of Active Male and Female Customers:
 - Determine the number of active male and female customers.
3. Customer Age Distribution: 
- Group customers based on age distribution into the following
categories: 
- Age between 18 and 30 
- Age between 31 and 45
 - Age above 45
4. Users with Available Balance Data: 
- Identify users with available balance data (balance > 0) and rank them
in ascending order.
5. Top 5 Balances: 
- Retrieve all information for customers with the top 5 balances.
6. Highest and Lowest Credit Score Values: 
- Find the highest and lowest credit score values.
7. Perform the following expressions: 
- Concatenate the first name and last name.
- Check if the commission is null, set it to zero. 
- Calculate the commission.
 - Calculate the total salary plus commission.
# Screenshots
1. Sum of Balances for Male and Female Customers:
![Screenshot 2024-06-11 224921](https://github.com/Ahmedelbermawy/ETL_Informtica_Power_Center/assets/133806022/915c9c27-638e-40f2-80b2-e197da937eaa)

Output 
• balance_sum.csv: Sum of balances for male and female customers.

2. Number of Active Male and Female Customers:
![Screenshot 2024-06-11 225036](https://github.com/Ahmedelbermawy/ETL_Informtica_Power_Center/assets/133806022/59431039-d354-41de-b253-8d120b01921b)
Output 
• active_count.csv: Number of active male and female

3. Customer Age Distribution:
![Screenshot 2024-06-11 225113](https://github.com/Ahmedelbermawy/ETL_Informtica_Power_Center/assets/133806022/08aa4962-b6ec-4354-b7a6-9a4b454e0993)
Output 
• Age Distribution Tables.

4. Users with Available Balance Data:
![Screenshot 2024-06-11 225219](https://github.com/Ahmedelbermawy/ETL_Informtica_Power_Center/assets/133806022/2ffb959c-b64c-421d-97c1-35bf37d75e50)
Output 
• tgt_has_balance_ff.csv: Users with available balance data.

5. Top 10 Balances:
![Screenshot 2024-06-11 225314](https://github.com/Ahmedelbermawy/ETL_Informtica_Power_Center/assets/133806022/edfc955b-b67f-4c54-939f-a5d22a1d07a8)
Output 
• rank_balance.csv: Information for customers with the top 10 balances.

6. Highest and Lowest Credit Score Values:
![Screenshot 2024-06-11 225347](https://github.com/Ahmedelbermawy/ETL_Informtica_Power_Center/assets/133806022/a39e8969-597b-4137-9cad-3d009a24bd6f)
Output 
• tgt_max_min_score.csv: Highest and lowest credit score values.

7. Perform the following expressions:
![Screenshot 2024-06-11 225423](https://github.com/Ahmedelbermawy/ETL_Informtica_Power_Center/assets/133806022/9ad3067a-be6c-449d-853f-c4605da2d829)
Output 
• tgt_employees_db.csv: Total SAL + Cal Commission.

# Usage:
1. Ensure that Informatica PowerCenter is installed and configured. 
2. Import the CSV files Churn_Modelling2.csv and Churn_Modelling3.csv, and import data from the Oracle HR schema into Informatica PowerCenter. 
3. Create mappings, transformations, and workflows to perform the specified tasks. 
4. Execute the workflows to generate the specified output files.
# Note: 
- Ensure the input CSV files are correctly mapped within Informatica PowerCenter.
- Validate the transformations and mappings to ensure accurate data processing. 
- Monitor the workflow execution for any errors or issues. 
- Adjust any parameters or configurations as needed to optimize performance and accuracy.


