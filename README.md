# BI Dashboard Project - Telco Company Customer Churn Analysis

Hello and welcome to our BI Mini Project's Code File which previously were implemented on Jupyter Notebook.

Our project is an analysis on the demographics, services, revenue models, but most importantly the churn factors, reasons and generators of a fictional Telco Company based in California, The United States of America.

**To have a look at the analysis, you may click the links on the Navbar:**

* _Demographics_ - For Customer Analysis
* _Services_ - For analysis of the services provided by the company
* _Revenue_ - For analysis of the companies revenue 
* _CSJ_ - For the analysis of the customer status - "Churned/Joined/Stayed"

**To view the Dashboard we created for this project, please visit here: https://plotly.com/~upade.arfah18/90/bi-mini-project-by-arfah-pooja-and-shweta/**

## Project Overview

### **Problem Definition:**

The Companies requirements are as follows:

A Telco Company based in the United States, has collected data for around four Quarters of their work and now would like to have a brief analysis of that data.

Utilising Business Intelligence, they would like to see the following:

**1. Their Customers**

Who are they, where are they from, what additional attributes they have

**2. Their Services**

What services are mostly bought, preferred or not opted for

**3. Their Revenue**

What’s the total revenue, the major contributing sources, what’s going wrong

**4. Their Churn/Joined/Stayed Status**

How many customers have churned, joined or stayed, what are the leading causes, who are churning?

### **Datasets used:**

1. [IBM Cognos Analytics sample dataset - Telco customer churn (11.1.3+)](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113) **(SOURCE)**
2. [Telco Customer Churn (11.1.3+) Dataset from Kaggle - Jack Chang](https://www.kaggle.com/ylchang/telco-customer-churn-1113) **(UPLOADER)**

## Dataset Overview

## **Context**

This sample data tracks a fictional telco company's customer churn based on a variety of possible factors. The churn column indicates whether or not the customer left within the last month. Other columns include gender, dependents, monthly charges, and many with information about the types of services each customer has. Source: IBM.

Inventory of Telco Assets

A variety of objects have been updated/created that work together to tell a comprehensive story:

**Telco churn:** This sample dashboard tracks a fictional telco company's customer churn based on a variety of factors. The Churn Label column indicates whether or not the customer left within the last month. Other columns include location, monthly charges, services, and customer lifetime value. Location: Team content > Samples > Dashboards.

**Quarterly churn update:** This sample story shows quarterly changes of customer churn in a fictional telco company, and which contract and location has the highest churn in order to decide the goals for the next quarter. The churn label column indicates whether or not the customer left within the last quarter. Location: Team content > Samples > Stories.

**Customer churn information by zip code:** This sample report is the drill-through target report for sample dashboard 'Telco churn' and sample story 'Quarterly churn update'. Location: Team content > Samples > Reports.

**Telco churn relationships:** This sample exploration tracks a fictional telco company's customer churn based on a variety of factors. The Churn Label column indicates whether or not the customer left within the last month. Other columns include location, monthly charges, services, and customer lifetime value. Location: Team content > Samples > Explorations.

**Telco customer churn:** This sample data module tracks a fictional telco company's customer churn based on a variety of possible factors. The churn column indicates whether or not the customer left within the last month. Other columns include gender, dependents, monthly charges, and many with information about the types of services each customer has. Source: IBM. Location: Team content > Samples > Data. 

**The Telco customer churn data module is composed of 5 uploaded files:**

Telcocustomerchurn_demographics.xlsx
Telcocustomerchurn_location.xlsx
Telcocustomerchurn_population.xlsx
Telcocustomerchurn_services.xlsx
Telcocustomerchurn_status.xlsx

## **Content**


### **Data**
Once the Base Samples are installed, if you navigate to Team Content > Samples > Data, you will see a data module that is named Telco customer churn. It contains 5 tables:

Demographics
Location
Population
Services
Status
Each table is described below.

**Demographics**

CustomerID: A unique ID that identifies each customer.

Count: A value used in reporting/dashboarding to sum up the number of customers in a filtered set.

Gender: The customer’s gender: Male, Female

Age: The customer’s current age, in years, at the time the fiscal quarter ended.

Senior Citizen: Indicates if the customer is 65 or older: Yes, No

Married: Indicates if the customer is married: Yes, No

Dependents: Indicates if the customer lives with any dependents: Yes, No. Dependents could be children, parents, grandparents, etc.

Number of Dependents: Indicates the number of dependents that live with the customer.

Location
CustomerID: A unique ID that identifies each customer.

Count: A value used in reporting/dashboarding to sum up the number of customers in a filtered set.

Country: The country of the customer’s primary residence.

State: The state of the customer’s primary residence.

City: The city of the customer’s primary residence.

Zip Code: The zip code of the customer’s primary residence.

Lat Long: The combined latitude and longitude of the customer’s primary residence.

Latitude: The latitude of the customer’s primary residence.

Longitude: The longitude of the customer’s primary residence.


**Population**

ID: A unique ID that identifies each row.

Zip Code: The zip code of the customer’s primary residence.

Population: A current population estimate for the entire Zip Code area.

**Services**

CustomerID: A unique ID that identifies each customer.

Count: A value used in reporting/dashboarding to sum up the number of customers in a filtered set.

Quarter: The fiscal quarter that the data has been derived from (e.g. Q3).

Referred a Friend: Indicates if the customer has ever referred a friend or family member to this company: Yes, No

Number of Referrals: Indicates the number of referrals to date that the customer has made.

Tenure in Months: Indicates the total amount of months that the customer has been with the company by the end of the quarter specified above.

Offer: Identifies the last marketing offer that the customer accepted, if applicable. Values include None, Offer A, Offer B, Offer C, Offer D, and Offer E.

Phone Service: Indicates if the customer subscribes to home phone service with the company: Yes, No

Avg Monthly Long Distance Charges: Indicates the customer’s average long distance charges, calculated to the end of the quarter specified above.

Multiple Lines: Indicates if the customer subscribes to multiple telephone lines with the company: Yes, No

Internet Service: Indicates if the customer subscribes to Internet service with the company: No, DSL, Fiber Optic, Cable.

Avg Monthly GB Download: Indicates the customer’s average download volume in gigabytes, calculated to the end of the quarter specified above.

Online Security: Indicates if the customer subscribes to an additional online security service provided by the company: Yes, No

Online Backup: Indicates if the customer subscribes to an additional online backup service provided by the company: Yes, No

Device Protection Plan: Indicates if the customer subscribes to an additional device protection plan for their Internet equipment provided by the company: Yes, No

Premium Tech Support: Indicates if the customer subscribes to an additional technical support plan from the company with reduced wait times: Yes, No

Streaming TV: Indicates if the customer uses their Internet service to stream television programing from a third party provider: Yes, No. The company does not charge an additional fee for this service.

Streaming Movies: Indicates if the customer uses their Internet service to stream movies from a third party provider: Yes, No. The company does not charge an additional fee for this service.

Streaming Music: Indicates if the customer uses their Internet service to stream music from a third party provider: Yes, No. The company does not charge an additional fee for this service.

Unlimited Data: Indicates if the customer has paid an additional monthly fee to have unlimited data downloads/uploads: Yes, No

Contract: Indicates the customer’s current contract type: Month-to-Month, One Year, Two Year.

Paperless Billing: Indicates if the customer has chosen paperless billing: Yes, No

Payment Method: Indicates how the customer pays their bill: Bank Withdrawal, Credit Card, Mailed Check

Monthly Charge: Indicates the customer’s current total monthly charge for all their services from the company.

Total Charges: Indicates the customer’s total charges, calculated to the end of the quarter specified above.

Total Refunds: Indicates the customer’s total refunds, calculated to the end of the quarter specified above.

Total Extra Data Charges: Indicates the customer’s total charges for extra data downloads above those specified in their plan, by the end of the quarter specified above.

Total Long Distance Charges: Indicates the customer’s total charges for long distance above those specified in their plan, by the end of the quarter specified above.

**Status**

CustomerID: A unique ID that identifies each customer.

Count: A value used in reporting/dashboarding to sum up the number of customers in a filtered set.

Quarter: The fiscal quarter that the data has been derived from (e.g. Q3).

Satisfaction Score: A customer’s overall satisfaction rating of the company from 1 (Very Unsatisfied) to 5 (Very Satisfied).

Satisfaction Score Label: Indicates the text version of the score (1-5) as a text string.

Customer Status: Indicates the status of the customer at the end of the quarter: Churned, Stayed, or Joined

Churn Label: Yes = the customer left the company this quarter. No = the customer remained with the company. Directly related to Churn Value.

Churn Value: 1 = the customer left the company this quarter. 0 = the customer remained with the company. Directly related to Churn Label.

Churn Score: A value from 0-100 that is calculated using the predictive tool IBM SPSS Modeler. The model incorporates multiple factors known to cause churn. The higher the score, the more likely the customer will churn.

Churn Score Category: A calculation that assigns a Churn Score to one of the following categories: 0-10, 11-20, 21-30, 31-40, 41-50, 51-60, 61-70, 71-80, 81-90, and 91-100

CLTV: Customer Lifetime Value. A predicted CLTV is calculated using corporate formulas and existing data. The higher the value, the more valuable the customer. High value customers should be monitored for churn.

CLTV Category: A calculation that assigns a CLTV value to one of the following categories: 2000-2500, 2501-3000, 3001-3500, 3501-4000, 4001-4500, 4501-5000, 5001-5500, 5501-6000, 6001-6500, and 6501-7000.

Churn Category: A high-level category for the customer’s reason for churning: Attitude, Competitor, Dissatisfaction, Other, Price. When they leave the company, all customers are asked about their reasons for leaving. Directly related to Churn Reason.

Churn Reason: A customer’s specific reason for leaving the company. Directly related to Churn Category.

## **Acknowledgements**
https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113

## **Changes made to the dataset:**

The only changes made to the dataset is the Quarter. Instead of 3 quarters we have allotted 4 Quarters and also the fact that the dataset only consists of data for Quarter 3, we have allocated date for Quarter 1, Qaurter 2, Quarter 3 and Quarter 4.

## **Libraries used**

1. [Plotly Python Open Source Graphing Library](https://plotly.com/python/)
2. [Plotly Chart Studio](https://plotly.com/chart-studio/)
3. Matplotlib - https://github.com/paishweta/BI_DASHBOARD_PLOTLY

## **Thank you very much!**

Telco Company Churn Analysis by:

* Pooja Shetty 
* Arfah Upade
* Shweta Pai

Feel free to reach out to us in case of any queries. 


















