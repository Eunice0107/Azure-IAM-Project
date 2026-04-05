# AZURE IAM Project -User and Access Management
This project demonstrates the implementation of Identity and Access Management (IAM) using Microsoft Azure. the goal was to securely manage user identities and control to resources using Role-Based Access Control (RBAC) and the principle of least Privilege.

Objectives

•	Create and manage users

•	Organize users into group

•	Assign roles based on job responsibilities 

•	Apply least privilege to reduce security risks

Project Steps

1.User Creation 
Creatred users
- admin.user
- dev.user
- audit.user
 Users were created using the same process to represent different roles within the organization with manually defined secure password.
  <img width="975" height="829" alt="image" src="https://github.com/user-attachments/assets/a63cbf76-0504-4500-a26c-c37a50a04e18" />

2.Group Creation
Created security Groups
-	Admin
-	Developers
-	Auditors
Security groups were created (Admins, Developers, Auditors) with clear descriptions to define their purpose and improvement
<img width="975" height="622" alt="image" src="https://github.com/user-attachments/assets/ab21b2d2-2b8d-4283-8ada-133f9119b5f0" />

3.Assigning User to Group

•	Admin-Admins
•	Developer-Developrs
•	Auditor-Auditors
Each user was assigned to their respective group to simplify acess control and ensure role-based to simplify access control and ensure role-based management . 
<img width="975" height="434" alt="image" src="https://github.com/user-attachments/assets/d0ae705a-0921-4540-b60c-144bbfdc0b43" />

4.Role Assignment (RBAC)

Roles were assigned at the subscription Level.
•	Admins-Owner (Full access)
•	Developers- Contributor (manage resources only)
•	Auditors-Reader (view-only access)
<img width="975" height="377" alt="image" src="https://github.com/user-attachments/assets/36ace1cc-2869-4eaa-99c4-f8ab6e5259e6" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/97bf431f-f3b6-4728-b4b7-6ad4aa5f4f34" />
<img width="975" height="478" alt="image" src="https://github.com/user-attachments/assets/30f5c37a-20e8-4c5a-acfb-9b4c6d078c99" />


5.Security Implementation 

Least Privilege
Access was granted based on the principle of least privilege ensuring users only have the permissions necessary to perform their roles.
<img width="975" height="554" alt="image" src="https://github.com/user-attachments/assets/07e6d588-cbfa-4d87-a49c-82414097fc77" />


6.Key Skills Demonstrated 

-	Identity and Access Management (IAM)
-	Role-Based Access Control (RBAC)
-	Azure user and Group management 
-	Security best practices 

7.Conculsion
This project demonstrates practical implementing of secure user and access management in a cloud environment, reflecting real-world enterprise practices. 
