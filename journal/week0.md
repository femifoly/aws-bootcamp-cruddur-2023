# Week 0 — Billing and Architecture
## INTRODUCTION
This is the week o of the AWS Cloud project bootcamp and this week I will undertake some tasks which are detailed below. I adopted the AWS Well Achitected Framework Pillars which helps to increase awareness of architectural best practices, address foundational areas that are often neglected and evaluate architectures using a consistent set of principles. The 6 pillars are:
* Operational Excellence
* Security
* Reliability
* Performance Efficiency
* Cost Optimization
* Sustainability


## USING CLOUD SHELL
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/cloudshell.png)

## GENERATING AWS CREDENTIALS
I was able to generate my AWS credentials but could not publish to Gitpod due to permission error. I have just installed my ubuntu server and will need to configure the remote ssh properly.

![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/gitpod.png)

## INSTALL AWS CLI
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/Screenshot%20from%202023-02-16%2018-22-27.png)



## CREATE IAM USER
It is best pratice to create IAM user(s) to gain access to permitted AWS services. For this project I have created an IAM user and thie processes are as follows:
* ##### Log in to the root user account to create the IAM user
![Root Login](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/Login%20to%20root.png)
* #### Click on add user to add a user account
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/user.png)
* #### Specifiy user details by typing in your user name and password then click Next
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/user1.png)
* #### Set user permission policies to determine what role and services that can be accessed
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/user2.png)
* #### Retrieve user sign-in details and save securely and click return to user list
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/user3.png)
* #### As you can see, we have succesfully created an IAM user!
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/userfinal.png)
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/userlog.png)
## CREATE BUDGET
AWS Budgets allows us to set custom cost and usage budgets that will alert us when budget thresholds are exceeded (or forecasted to exceed). We can also create budgets to track your aggregate Reservation and Savings Plans utilization and coverage metrics. for this project, I will create a budget that will help me to monitor my account spendings as the project develops. The processes to create budgets are as follows:
* #### Type Budget in the AWS Console search bar and select AWS Budgets from the drop down menu
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/Budgetsearch.png)

* #### Click on create budgets and select the Customized (Advanced) setting to enable you set up your budget
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/createbudget1.png)

* #### Configure your budget alert and click next to create budget
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/creatbudget2.png)

![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/alert1.png)

* #### Budget and budget alert has been successfully created!
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/cashbudget.png)
* #### We can also follow the same process to setup budget for our AWS credits
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/budgetfinal.png)

![Cruddur Conceptual Diagram](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/Screenshot%20from%202023-02-14%2000-46-31.png)
**[Cruddur Conceptual Diagram](https://lucid.app/lucidchart/a82b5334-0949-4071-addf-800a00476dd5/edit?viewport_loc=-64%2C148%2C2125%2C1123%2C0_0&invitationId=inv_dc1c60e9-8dc0-4fa8-b85b-58ec142a21f7)**

---

![Cruddur Logical Diagram](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/Screenshot%20from%202023-02-16%2009-44-42.png)
**[Cruddur Logical Diagram](https://lucid.app/lucidchart/a82b5334-0949-4071-addf-800a00476dd5/edit?viewport_loc=-64%2C148%2C2125%2C1123%2C0_0&invitationId=inv_dc1c60e9-8dc0-4fa8-b85b-58ec142a21f7)**
