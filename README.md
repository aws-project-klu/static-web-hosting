# AWS Project - Static Web Hosting on Amazon EC2
This project demonstrates the deployment of a static website on an Amazon EC2 Linux instance, configured with HTTPD and hosted on port 80. The project highlights the process of setting up web hosting for the KLU University website using AWS.

## 🚀 Project Highlights
- **VPC Creation:** Set up a custom Virtual Private Cloud (VPC) to manage network configurations.
- **Instance Deployment:** Launched an Amazon EC2 Linux instance for hosting the static website.
- **Configuration:** Configured HTTPD on the instance to enable web hosting via port 80.
- **Secure Connection:** Connected to the instance securely using PuTTY and the AWS Management Console.

## 🎯 Objective
To demonstrate the deployment of a static website using AWS services, enabling seamless hosting and accessibility for the KLU University website.

## 🛠 Technologies Used
- **Amazon Web Services (AWS):** EC2, VPC
- **Linux:** Server environment
- **HTTPD:** Apache Web server configuration
- **PuTTY:** Secure connection to EC2 instance

## 🌟 Outcome
Successfully hosted a static website for KLU University on an AWS EC2 instance, showcasing practical skills in cloud infrastructure, networking, and web hosting.

**Authors:**
- G. G. Sanjana (190030485)
- N. S. P. Priyanka (190031190)

**Department:** Computer Science and Engineering, K L University

### 📂 Steps Included:
We have included detailed step-by-step instructions with screenshots below, showcasing the process of hosting a static website on AWS EC2. One approach uses the AWS "Connect" option, while the other involves connecting to the instance via PuTTY.  

Steps for static web hosting to connect kluniversity website on EC2 linux with httpd port 80

STEP 1: Login into aws console
![image](https://github.com/user-attachments/assets/71ab52b4-8763-4220-aa44-ce194e65c1f5)

STEP 2: NavIGATE TO VPC SERVICE
![image](https://github.com/user-attachments/assets/939988a6-de9d-446c-90ce-c954f9a0286f)

STEP 3: LaUNCH vpc wizard
![image](https://github.com/user-attachments/assets/a816e1e1-6469-4f3f-8e9f-9f4dcd2ae751)

STEP 4: select vpc with a single public subnet
![image](https://github.com/user-attachments/assets/5585b344-d70e-481b-97bd-94470ab2df9f)

STEP 5&6: Change VPC Name and create vpc
![image](https://github.com/user-attachments/assets/a3db6bf9-fe70-4cd8-a15e-2635fc57f566)

STEP 7: VPC is successfully created 
![image](https://github.com/user-attachments/assets/662ede96-5cc3-47f7-a84b-2d2586475766)

STEP 8: Check new vpc, internet gateways and route tables
![image](https://github.com/user-attachments/assets/d68df6b1-d045-4461-8007-6ce365dfa108)
![image](https://github.com/user-attachments/assets/c7720901-5212-43b4-bb34-dac7209ca7f7)
![image](https://github.com/user-attachments/assets/4fb40f7d-ba84-4e4b-8da2-9429b3fdc599)



***CREATE INSTANCE***
STEP 9: navigate to ec2 service 
![image](https://github.com/user-attachments/assets/0560b002-3dea-43d2-83aa-d75646d3a420)

STEP 10: launch instance 
![image](https://github.com/user-attachments/assets/103ff228-6756-435b-a5ad-b014c06ecd05)

STEP 11: Choose amazon lnux 2 AMI 
![image](https://github.com/user-attachments/assets/c943c9b2-c0e7-4889-928a-6b1f2a54dd00)

STEP 12: Choose T2.micro instance type
![image](https://github.com/user-attachments/assets/76552e42-3e16-49cb-95e1-b4c7fb692ef5)

STEP 13: Choose newly created vpc
![image](https://github.com/user-attachments/assets/ed264bdc-8687-42bf-8ab4-a58f2cea6feb)

STEP 14: enable using subnet setting
![image](https://github.com/user-attachments/assets/e0024c42-52d1-44e6-811e-aafa8b66b557)

STEP 15: change security group name and add http, all traffic rules
![image](https://github.com/user-attachments/assets/a700b37c-82fd-4520-83aa-1cfe7c623ea3)

STEP 16: review and launch instance
![image](https://github.com/user-attachments/assets/bf725244-ad91-46b4-9201-ad37113688d4)

STEP 17: create a new key pair
![image](https://github.com/user-attachments/assets/ad835079-dd82-4b95-a092-631679a61612)

STEP 18: download key pair
![image](https://github.com/user-attachments/assets/f595a617-2146-4c0a-b28a-a473cb781393)

STEP 19: launch instance
![image](https://github.com/user-attachments/assets/80746533-c879-4cbf-8e5a-3ccd3db2285c)

STEP 20: wait till 2/2 status check is passed
![image](https://github.com/user-attachments/assets/ad1a6e78-14f4-47dd-96b9-88f1d003bd5d)
![image](https://github.com/user-attachments/assets/0e5219fc-5993-4142-9210-703c01205493)


***CONNECTING BY CLICKING CONNECT***
For the next steps, please click on the [link](https://github.com/aws-project-klu/static-web-hosting/blob/main/clicking-connect.md)

