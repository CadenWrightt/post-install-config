<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>

 ![Screenshot 2024-12-06 115300](https://github.com/user-attachments/assets/634d48f3-ad5f-4ea4-b861-e8fc762b9510)
![Screenshot 2024-12-06 115345](https://github.com/user-attachments/assets/69b601a3-0286-45f3-a264-dd118c5a5a20)

</p>
<p>
Acknowledge Agent Panel vs Admin Panel
</p>
<br />

<p>

 ![Screenshot 2024-12-06 121227](https://github.com/user-attachments/assets/6cbfa411-6c04-4c2d-b967-c4ddc643d6b2)
![Screenshot 2024-12-06 121252](https://github.com/user-attachments/assets/f55ac2ca-2b52-4a38-9f7f-997ea93eee7b)
![Screenshot 2024-12-06 121319](https://github.com/user-attachments/assets/1492d81f-ab15-477b-9a19-b9153f496a57)
![Screenshot 2024-12-06 121339](https://github.com/user-attachments/assets/cdb8c50c-b887-43f6-aa28-407e30e48aad)
![image](https://github.com/user-attachments/assets/1f76fda3-56d7-40cc-a007-36729067c9d6)

</p>
<p>
Configure Roles (for grouping permissions) Admin Panel -> Agents -> Roles Create a Supreme Admin Role |
 Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking) Admin Panel -> Agents -> Departments Create a SysAdmin Department |
  Configure Teams, Admin Panel -> Agents -> Teams (Pull Agents from different Departments) Create a Online Banking Team |
  Configure Agents (workers) Admin Panel -> Agents -> Add New Jane (Dept: SysAdmins) John (Dept: Support) |
  (UNCHECK: unregistered users can create tickets)

</p>
<br />

<p>

 ![Screenshot 2024-12-06 121418](https://github.com/user-attachments/assets/c28ff47f-b131-4db5-843a-d2f5a834bb09)

</p>
<p>
Configure Users (customers) Agent Panel -> Users -> Add New Create Karen
</p>
<br />

<p>

 ![Screenshot 2024-12-06 121503](https://github.com/user-attachments/assets/edd2320a-caff-4770-b726-7f2d371bfa6c)

 Configure SLA,  Admin Panel -> Manage -> SLA, Sev-A (Grace Period: 1 hour, Schedule: 24/7) Sev-B (Grace Period: 4 hours, Schedule: 24/7) Sev-C (Grace Period: 8 hours, Business Hours) |
 
![Screenshot 2024-12-06 121519](https://github.com/user-attachments/assets/c5f0b67e-a95b-4b21-9359-f91fde1b7579)

</p>
<p>
Configure Help Topics (For when users create a ticket) Admin Panel -> Manage -> Help Topics, Create these Help Topics Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, Other

</p>
<br />
