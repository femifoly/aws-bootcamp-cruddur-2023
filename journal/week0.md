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
## GENERATING AWS CREDENTIALS
## INSTALL AWS CLI
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
* #### As you can see, we have succefully created an IAM user!
![](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/userfinal.png)
## CREATE BUDGET



![Cruddur Conceptual Diagram](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/Screenshot%20from%202023-02-14%2000-46-31.png)
**[Cruddur Conceptual Diagram](https://lucid.app/lucidchart/a82b5334-0949-4071-addf-800a00476dd5/edit?viewport_loc=-64%2C148%2C2125%2C1123%2C0_0&invitationId=inv_dc1c60e9-8dc0-4fa8-b85b-58ec142a21f7)**

---

![Cruddur Logical Diagram](https://github.com/femifoly/aws-bootcamp-cruddur-2023/blob/main/HomeWork%20Files/Screenshot%20from%202023-02-16%2009-44-42.png)
**[Cruddur Logical Diagram](https://lucid.app/lucidchart/a82b5334-0949-4071-addf-800a00476dd5/edit?viewport_loc=-64%2C148%2C2125%2C1123%2C0_0&invitationId=inv_dc1c60e9-8dc0-4fa8-b85b-58ec142a21f7)**
