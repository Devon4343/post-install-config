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

1).Admin/Analyst Login Page http://localhost/osTicket/scp/login.php

2).Configure Roles (for grouping permissions) Admin Panel, Agents, Roles, Supreme Admin.
  
3).Configure Departments Admin Panel -> Agents -> Departments in SysAdmins.

4).Allow anyone to create tickets Admin Panel -> Settings -> User Settings, Registration Required: Require registration and login to create tickets. 

5).Configure Agents, Admin Panel -> Agents -> Add New, Configure Users, Agent Panel -> Users -> Add New. 

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/EJIF1y7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log on to the admin page http://localhost/osTicket/scp/login.php on the agent panel i can configure roles for grouping permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/F8s3HyE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the Admin Panel i can set the conditons for anyone to be able to create a ticket with settings -> user settings in which i can require the user to register to create a ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/6wE3J8A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents in the Admin Panel, Admin -> Agents -> New Agent, Configure Users in the Agent Panel -> Users -> Add New. 
</p>
<br />
