<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
In this project I will demonstrate installing and configuring Active Directory onto a Virtual Machine. After configuration I will demonstrate the process
of adding users into the system.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Install Active Directory 
- Step 2: Create Organizational Unit
- Step 3: New User Creation 
- Step 4: Configure Remote Desktop for Non Administrative users.
- Step 5: Create users using Powershell

<h2>Deployment and Configuration Steps</h2>

<p>
<<img width="1440" alt="AD Domain Services Install" src="https://github.com/user-attachments/assets/b5f82d67-32db-4eb7-888a-6494fd239bca" />
</p><img width="1440" alt="AD Domain Services Install p2" src="https://github.com/user-attachments/assets/40dda7dc-4683-4743-a1d5-20d52f8bc5fd" />
<p>
Step 1: Active Directory Installation: When installing Active Directory you have to activate the active directory domain services because they provide all the core functions of Active Directory. Your server can not function as a domain controller with out these services installed. These services are essential for managing your domain including user logins, passwords, permissions, and policies. 

<p>
<img width="1440" alt="OU CREATION" src="https://github.com/user-attachments/assets/d5c128e0-7ee6-41d4-a5a3-38a65c02d8bc" />
</p>
<p>Step 2: Organizational Unit Creation: Organizational units within active directory are a key element for organizing, managing and securing the resources of your company. Organizational units allow you to group specific users and computers based on their department, location or function. 
</p>
<br />

<p><img width="1440" alt="New User Creation" src="https://github.com/user-attachments/assets/2ce34913-8bbb-4de5-90a5-fcc0af5e3b4b" />
</p><img width="1440" alt="Creating Users in powershell" src="https://github.com/user-attachments/assets/350487c3-d53c-446b-b67a-7fe96bb902ff" />
<img width="1440" alt="Creating Users in powershell p2" src="https://github.com/user-attachments/assets/8fc55ac5-f450-458a-a576-fc88349f6a0a" />
<p> Step 3: New User Creation: Creating users in Active directory allows you to manage the employees working within your organization. Users can login to any computer that is within your organization's domain using one set of creditials. This centralized login system allows for you to have a more secure environment for your organization's resources. 
<br />
<img width="1440" alt="RDP config for non admins" src="https://github.com/user-attachments/assets/16238122-eb5b-4501-b188-ff51756b60c0" />
Step 4: Configure Remote Desktop for Non Administrative Users : By default only administrative users have access to remote desktop controls. Depending on their role within the organization some users will need acess to remote desktop controls. Allowing access to non administrative users allows them to complete their task without giving them acess to more than they need. This helps keep high level resources and information secure from malicious use. 
