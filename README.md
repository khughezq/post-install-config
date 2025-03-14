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
- Configuring Users
- Configuring SLA's
- Configuring Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="716" alt="image" src="https://github.com/user-attachments/assets/1d192cc7-7931-4856-b24b-72776e173e2d" />

<img width="718" alt="image" src="https://github.com/user-attachments/assets/ea9069fb-7ed4-4f2c-b9f3-85052a98b5f3" />


</p>
<p>
1. First I wanted to configure a Supreme Admin Role within osTicket. To do this you must be in the Admin Panel, go to Agents, then to Roles, and click on Add New Role. Then you can create a name for your role and assign your permissions.
</p>
<br />

<p>
<img width="711" alt="image" src="https://github.com/user-attachments/assets/b3ae6627-0924-4adf-9645-26e9386650e6" />

<img width="502" alt="image" src="https://github.com/user-attachments/assets/25e26a71-92f4-4634-9e7a-f9d60376f520" />

</p>
<p>
2. Next, we will configure our SysAdmins department. To accomplish this you must be in the Admin Panel, go to Agents, then to Departments, and click on Add New Department. 
</p>
<br />

<p>
<img width="713" alt="image" src="https://github.com/user-attachments/assets/7ee7d2fa-400b-4e84-a3c5-a4e1c5a47267" />

<img width="502" alt="image" src="https://github.com/user-attachments/assets/38ae5eec-501c-48b0-bbc2-670f0ffe2f88" />

</p>
<p>
3. Then I configured a Team so that we can add Agents to work on projects together in different departments. I created an Online Banking team. To do this we start in our Admin Panel, go to Agents, then Teams, and click on Add New Team. 
</p>
<br />

<p>
<img width="494" alt="image" src="https://github.com/user-attachments/assets/fce4fbd4-ceee-4c2d-9481-1fe11ce72a82" />

</p>
<p>
4. To allow end users to create tickets we start in the Admin Panel, go to Settings, and then go to Users. 
</p>
<br />

<p>
<img width="527" alt="image" src="https://github.com/user-attachments/assets/a30e91aa-f7e6-4c3f-a405-00ec278bdfa8" />

<img width="501" alt="image" src="https://github.com/user-attachments/assets/c64dd888-0fdc-4295-a2d1-ed4f9909334d" />

</p>
<p>
5. In order to add New Agents (workers) we go to our Admin Panel, go to Agents, and click on Add New Agents. I created two Agents, Jane and John Doe. For Jane, I put her in the SysAdmin Department, gave her Supreme Admin Access, and put her on the Online Banking Team. For John, his primary department will be the Support Department with view only access granted and he is not a part of the Online Banking Team. 
</p>
<br />

<p>
<img width="469" alt="image" src="https://github.com/user-attachments/assets/c6a212e9-c89f-4bf0-abbc-b8bbdd081835" />

<img width="497" alt="image" src="https://github.com/user-attachments/assets/c1fc1b6a-817e-4244-9619-b985d81e878a" />

</p>
<p>
6. To Add New Users we start in the Agent Panel, go to Users, and click on Add User. After, we can see Karen in our User Directory.  
</p>
<br />

<p>
<img width="470" alt="image" src="https://github.com/user-attachments/assets/2658d97d-3bcb-4a17-8039-a641a369b12d" />


<img width="494" alt="image" src="https://github.com/user-attachments/assets/dfeb7730-ab1f-4faa-a337-471b1d984515" />


</p>
<p>
7. After that we are going to Configure three different levels of SLA's. To do this we go to the Admin Panel, Manage, and Add New SLA Plan. Sev-A (Grace Period: 1 hour, Schedule: 24/7), Sev-B (Grace Period: 4 hours, Schedule: 24/7), Sev-C (Grace Period: 8 hours, Business Hours).
</p>
<br />

<p>
<img width="711" alt="image" src="https://github.com/user-attachments/assets/1a97c3ef-0cc0-4a07-81c4-a5fbff456158" />

</p>
<p>
8. Finally, I configured Help Topics for when users create a ticket. To create this we go to the Admin Panel, Manage, and then to Help Topics. All the highlighted Help Topics were added.  
</p>

