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

<h2>Configuration Steps</h2>

<b>Configure Roles (Permission Grouping)</b>
<p>To begin managing agent permissions, navigate to:
<b>Admin Panel → Agents → Roles</b>.
Here, create a new role named <b>“Supreme Admin”</b> and assign it full access privileges.</p>
  
![image](https://github.com/user-attachments/assets/b8341fa2-8893-46aa-a7a0-a7d7b92ed44b)

<b>Create Teams (Cross-Department Collaboration)</b>
<p>Teams allow you to group agents across different departments for specific functions. Navigate to:
<b>Admin Panel → Agents → Teams</b>.
Create a team named <b>“Online Banking”</b>.</p>
  
![image](https://github.com/user-attachments/assets/49b662c9-a584-4c71-a61c-d832d3e1cbdd)

<b>Set Up Departments (Ticket Visibility Control)</b>
<p>Next, configure departments to control which agents can see and manage specific types of tickets. Go to:
<b>Admin Panel → Agents → Departments</b>.
Create a department called <b>“SysAdmins”</b>.</p>
  
![image](https://github.com/user-attachments/assets/24a3fe15-d94c-49ee-acd6-984bdc994592)

<b>Adjust User Access Settings</b>
<p>To control how users submit tickets, go to:
<b>Admin Panel → Settings → User Settings</b>.
Uncheck <b>“Require registration and login to create tickets”</b> to allow unregistered users to submit tickets freely.</p>
  
![image](https://github.com/user-attachments/assets/1efb876a-6d5b-448f-8b7e-5d3bc59f2c27)

<b>Add Agents (Support Staff)</b>
<p>Now you can start adding your IT support agents. Navigate to:
<b>Admin Panel → Agents → Add New</b>.
Add the following agents as examples:

  - Jane — assign to SysAdmins department

  - John — assign to Support department</p>
  
![image](https://github.com/user-attachments/assets/de8c23f0-4092-49a6-83e6-88e5bb14347c)

<b>Add Users (Customers)</b>
<p>To simulate customer interactions, add end users via:
<b>Agent Panel → Users → Add New</b>.
Create users such as:

  - Karen

  - Ken

These users will represent clients or internal staff submitting tickets.</p>
  
![image](https://github.com/user-attachments/assets/d98ad97f-3f5f-46f6-9b21-10f8b5086b91)

<b>Set Up SLA Plans (Ticket Time Expectations)</b>
<p>Service Level Agreements help define response expectations. Go to:
<b>Admin Panel → Manage → SLA</b>.
Create three SLA plans:
  
  - Sev-A — 1 hour grace period, 24/7 support

  - Sev-B — 4 hour grace period, 24/7 support

  - Sev-C — 8 hour grace period, business hours only</p>
  
![image](https://github.com/user-attachments/assets/c7639a23-979f-4b45-af36-d7dc50630aa9)

<b>Configure Help Topics (Ticket Categories)</b>
<p>Finally, create help topics to guide users when submitting new tickets. Navigate to:
<b>Admin Panel → Manage → Help Topics</b>.
Add the following topics:

  - Business Critical Outage

  - Personal Computer Issues

  - Equipment Request

  - Password Reset

  - Other

These help topics ensure tickets are categorized properly and routed to the right teams.</p>

![image](https://github.com/user-attachments/assets/60cb952f-0991-4066-96ee-fc5f0f3597f9)
