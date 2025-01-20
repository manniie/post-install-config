<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This section outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

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
- Make Registration Required To Make Tickets
- Configure Agents (Workers)
- Confgiure Users (Customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3>Configure Roles For Grouping Permissions</h3>

![image](https://github.com/user-attachments/assets/be2f473c-0526-4231-8c9b-a0b74f016f62)

<p>
A Supreme Admin role created with all permissions.
</p>
<hr>
<h3>Configure Departments For System Admins</h3>

![image](https://github.com/user-attachments/assets/f94602f8-28c1-46d8-a57e-53aeff0569ca)

<p>
Configured a department called System Admins so agents can be assigned to this department.
</p>
<hr>
<h3>Configured Teams Called Online Banking</h3>

![image](https://github.com/user-attachments/assets/88b1c41e-9a7c-4375-ba45-5ea06062c2db)

<p>Configured a team called Online Banking so that you can organize a group of people from different departments.</p>
<hr>
<h3>Require Registration For Creating Tickets</h3>

![image](https://github.com/user-attachments/assets/17aa31de-0c11-4a32-9494-08d1db4bce87)

<p>Configured osTickets to require registration and login to create tickets</p>
<hr>
<h3>Configured Agents Named John & Jane Doe</h3>

![image](https://github.com/user-attachments/assets/419324dd-7f40-4643-b84b-042c15e1a4ba)

<p>Created two agents named John & Jane Doe and added to System Admins department.</p>
<hr>
<h3>Configured Users Karen & Ken Doe</h3>

![image](https://github.com/user-attachments/assets/00c9abd5-4040-4e1c-bf46-b3b4afab6bac)

<p>Created the users Karen and Ken so they can create tickets.</p>
<hr>
<h3>Configured SLA Rules</h3>

![image](https://github.com/user-attachments/assets/f1e569fb-e043-4705-a925-265ebe79b590)

<p>Configured the SLA to have Sev-A [Grace Period - 1 Hour, Schedule - 24/7] Sev-B [Grace Period - 4 Hours, Schedule - 24/7] and Sev-C [Grace Period - 8 Hours, Schedule - Business Hours]. </p>
<hr>
<h3>Configured Help Topics For When Users Create A Ticket</h3>

![image](https://github.com/user-attachments/assets/7751fa56-5cde-4926-9609-209c226526ea)

<p>Created different help topics that are popular topics for ticket support to answer and categorize each type of ticket.</p>
<hr>
