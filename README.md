# Azure-IAM-Project
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
  
2.Group Creation
Created security Groups
-	Admin
-	Developers
-	Auditors
Security groups were created (Admins, Developers, Auditors) with clear descriptions to define their purpose and improvement

3.Assigning User to Group

•	Admin-Admins
•	Developer-Developrs
•	Auditor-Auditors
Each user was assigned to their respective group to simplify acess control and ensure role-based to simplify access control and ensure role-based management . 

4.Role Assignment (RBAC)

Roles were assigned at the subscription Level.
•	Admins-Owner (Full access)
•	Developers- Contributor (manage resources only)
•	Auditors-Reader (view-only access)

5.Security Implementation 

Least Privilege
Access was granted based on the principle of least privilege ensuring users only have the permissions necessary to perform their roles.

6.Key Skills Demonstrated 

-	Identity and Access Management (IAM)
-	Role-Based Access Control (RBAC)
-	Azure user and Group management 
-	Security best practices 

7.Conculsion
This project demonstrates practical implementing of secure user and access management in a cloud environment, reflecting real-world enterprise practices. 
