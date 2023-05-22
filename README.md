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

- Item 1: Configure Roles
- Item 2: Configure Departments
- Item 3: Configure Teams
- Item 4: Allow anyone to create tickets
- Item 5: Configure Agents (workers)
- Item 6: Configure Users (customers)
- Item 7: Configure SLA
- Item 8: Configure Help Topics


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/R35RNH5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/YurNDqT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/BREX28J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles: 
    A. Admin Panel -> Agents -> Roles -> Supreme Admin
    B. Permissions-> Click all the permissions, go to each permissions tab and click all the boxes there as well save.
I have created a new role and named it supreme admin.
</p>
<br />

<p>
<img src="https://i.imgur.com/hcsegU0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/ZI0xSV4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments:
    A. Admin Panel -> Agents -> Create Departments-> System Administrators-> Default Settings
I have added a new department named System Administrators with default settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/mlo8BRn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/6qJpdhq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams:
    A. Admin Panel -> Agents -> Teams-> Level II Support -> Create Team
I have created a new team named Level II Support and added myself as a user in the team.
</p>
<br />

<p>
<img src="https://i.imgur.com/BO1T3aM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets:
    A. Admin Panel -> Settings -> User Settings
    B. Registration Required: This requires registration and login to create tickets; make sure this box is unchecked
I have allowed anyone to create tickets by unchecking the 'Registration Required' box.
</p>
<br />

<p>
<img src="https://i.imgur.com/3SY6iDD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/7dqG9vB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers): 
    A. Admin Panel -> Agents -> Add New
      i. Jane
      ii. John
I have added new agents Jane doe and John doe.
</p>
<br />

<p>
<img src="https://i.imgur.com/kmZpFDs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/sQ4qgi4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/9EjRwh4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers): 
    A. Switch to Agent Panel -> Users -> Add New
      i. Karen
      ii. Ken
I have added customers Karen Karen and Ken Ken.
</p>
<br />

<p>
<img src="https://i.imgur.com/5RKqon5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/7UFdbU5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA:
    A. Admin Panel -> Manage -> SLA
      i. Sev-A (1 hour, 24/7)
      ii. Sev-B (4 hours, 24/7)
      iii. Sev-C (8 hours, business hours)
I have created the SLA for the help topics. A service-level agreement (SLA) defines the level of service and standards expected by a customer from the help desk.
</p>
<br />

<p>
<img src="https://i.imgur.com/OxKRkDd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/LTl3OpG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics:
    A. Admin Panel -> Manage -> Help Topics
      i. Business Critical Outage
      ii. Personal Computer Issues
      iii. Equipment Request
       iv. Password Reset
I have created 4 help topics. A Help Topic is an identifier used to help the customer choose what problem their experience and helps agents with identifying solutions in a timely manner.
</p>
<br />
