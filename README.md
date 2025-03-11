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

- Configuring Roles (for grouping permissions)
- Configuring Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allowing End Users to create tickets
- Configuring Agents

<h2>Configuration Steps</h2>

<p>
![image](https://github.com/user-attachments/assets/45bbcadd-0c85-4327-9b99-bde998dc421b)
![image](https://github.com/user-attachments/assets/2472dc13-cd81-4201-a5d0-ea8e64597a68)

</p>
<p>
In order, to configure a Supreme Admin Role within osTicket you must be in the Admin Panel, go to Agents, then to Roles, and click on Add New Role.
</p>
<br />

<p>
![image](https://github.com/user-attachments/assets/9c3896bd-bc9b-4344-9405-0e63905bcade)
![image](https://github.com/user-attachments/assets/988626ef-cf6f-4a27-8c1e-e6a3c745bf16)

</p>
<p>
Next, we will configure our SysAdmins department. To accomplish this you must be in the Admin Panel, go to Agents, then to Departments, and click on Add New Department. 
</p>
<br />

<p>
![image](https://github.com/user-attachments/assets/d3a3fead-6ec9-4920-990b-03318a855d45)
![image](https://github.com/user-attachments/assets/f9a8c811-1fb6-4c2e-92d7-b0175851e4bb)

</p>
<p>
Configuring Teams so that we can add Agents to Onwork on projects together in different departments. To do this we start in our Admin Panel, go to Agents, then Teams, and click on Add New Team. 
</p>

<p>
![image](https://github.com/user-attachments/assets/cd98e548-d2e6-4d5c-9c9e-418b402a92e2)

</p>
<p>
To allow end users to create tickets we start in the Admin Panel, go to Settings, and then go to Users. 
</p>

<p>
![image](https://github.com/user-attachments/assets/90731ea6-fbcf-4d50-8439-d378a97295d6)
![image](https://github.com/user-attachments/assets/f0e628b5-ba4f-4f88-ab14-de95649ad9da)

</p>
<p>
In order to Add New Agents (workers) we go in our Admin Panel, go to Agents, and click on Add New Agents. I created two Agents Jane and John Doe. For Jane, I put her in the SysAdmin Department, gave her Supreme Admin Access, and put her on the Online Banking Team. For John, his primary department will be the Support Department with view only access granted and he is not a part of the Online Banking Team. 
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
