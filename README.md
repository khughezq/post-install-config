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
![image](https://github.com/user-attachments/assets/9c3896bd-bc9b-4344-9405-0e63905bcade)
![image](https://github.com/user-attachments/assets/988626ef-cf6f-4a27-8c1e-e6a3c745bf16)

</p>
<p>
2. Next, we will configure our SysAdmins department. To accomplish this you must be in the Admin Panel, go to Agents, then to Departments, and click on Add New Department. 
</p>
<br />

<p>
![image](https://github.com/user-attachments/assets/d3a3fead-6ec9-4920-990b-03318a855d45)
![image](https://github.com/user-attachments/assets/f9a8c811-1fb6-4c2e-92d7-b0175851e4bb)

</p>
<p>
3. Configuring Teams so that we can add Agents to Onwork on projects together in different departments. To do this we start in our Admin Panel, go to Agents, then Teams, and click on Add New Team. 
</p>

<p>
![image](https://github.com/user-attachments/assets/cd98e548-d2e6-4d5c-9c9e-418b402a92e2)

</p>
<p>
4. To allow end users to create tickets we start in the Admin Panel, go to Settings, and then go to Users. 
</p>

<p>
![image](https://github.com/user-attachments/assets/90731ea6-fbcf-4d50-8439-d378a97295d6)
![image](https://github.com/user-attachments/assets/f0e628b5-ba4f-4f88-ab14-de95649ad9da)

</p>
<p>
5. In order to Add New Agents (workers) we go in our Admin Panel, go to Agents, and click on Add New Agents. I created two Agents Jane and John Doe. For Jane, I put her in the SysAdmin Department, gave her Supreme Admin Access, and put her on the Online Banking Team. For John, his primary department will be the Support Department with view only access granted and he is not a part of the Online Banking Team. 
</p>

<p>
![image](https://github.com/user-attachments/assets/2a3380a8-304f-433d-a00e-54070dce45b5)
![image](https://github.com/user-attachments/assets/30f1ca51-a3d5-4835-a2d3-b524f6ac59ed)

</p>
<p>
6. To Add New Users we start in the Agent Panel, go to Users, and click on Add User. After we can see Karen in our User Directory.  
</p>

<p>
![image](https://github.com/user-attachments/assets/77530b5d-b037-4979-ab8e-bbe948d43922)
![image](https://github.com/user-attachments/assets/db7625a4-df7e-4569-9eb6-011445b6fe30)
![image](https://github.com/user-attachments/assets/193661ce-efe8-4433-84f5-739508b92c71)
![image](https://github.com/user-attachments/assets/11d7e32d-254c-4e28-87fc-973b4d2a2533)

</p>
<p>
7. Then we are going to Configure three different levels of SLA's. To do this we go to the Admin Panel, Manage, and Add New SLA Plan. Sev-A (Grace Period: 1 hour, Schedule: 24/7), Sev-B (Grace Period: 4 hours, Schedule: 24/7), Sev-C (Grace Period: 8 hours, Business Hours).
</p>

<p>
![image](https://github.com/user-attachments/assets/b83ef0a9-e59c-44cd-a3d9-a1fda0069ca6)

</p>
<p>
8. Finally, will configure Help Topics for when users create a ticket. To create this we go to the Admin Panel, Manage, and then to Help Topics. 
</p>

