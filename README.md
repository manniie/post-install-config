<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
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

<p>1). The first step is to log into the adminuser account. The username should be "adminuser" and "Password1". Create a role which is used for grouping permissions. In this example, we'll be creating a role called "Supreme Admin" which will have all permissions eanbled. </p>

<p>To create this role click the Admin Panel.</p>

![image](https://github.com/user-attachments/assets/2415ae2e-5ff3-44d8-898e-a4568e105078)

<p>Hover over "Agents" and click "Roles" and then click on "Add New Role"</p>

![image](https://github.com/user-attachments/assets/58c7d1cf-7d5f-4fba-8bee-5de79bb90c8f)

<p>Fill out the name of the role which is "Supreme Admin" </p>

![image](https://github.com/user-attachments/assets/dc6383a4-4d14-4b1e-a9e3-36b24f93f5f9)

<p>Next we want to assign all permissions to this role by click Permissions and enabling all the permissions. 

Make sure to select all permissions in all of the categories then save.</p>

![image](https://github.com/user-attachments/assets/842087ff-6521-4f93-9063-608bee73dbe1)

![image](https://github.com/user-attachments/assets/4beb4d4f-a801-4bbf-8d3e-ca56e233e4ae)

![image](https://github.com/user-attachments/assets/510b1dad-bf60-448b-8ac7-ac17ea39c148)

<hr>
<h3>Configure Departments For System Admins</h3>

<p>2). Next click on Departments and select Add New Department.</p>

![image](https://github.com/user-attachments/assets/6a4c2c8e-4855-4c65-b80e-9e96b994bc1e)

<p>Put the name of the Department as "SysAdmins" and click save.</p>

![image](https://github.com/user-attachments/assets/59c00b43-a669-4c82-8487-cbbf2c51868f)

<p>Configured a department called System Admins so agents can be assigned to this department.</p>

<hr>
<h3>Configured Teams Called Online Banking</h3>

<p>3). Third step is to click Teams and select Add New Teams.</p>

![image](https://github.com/user-attachments/assets/a629eacc-289d-4c7c-81d5-ce40186c4286)

<p>Put the name of the Teams as "Online Banking" and click "Create Team".</p>

![image](https://github.com/user-attachments/assets/88b1c41e-9a7c-4375-ba45-5ea06062c2db)

<p>Configured a team called Online Banking so that you can organize a group of people from different departments.</p>
<hr>
<h3>Require Registration For Creating Tickets</h3>

<p>4). Go to the Settings section</p>

![image](https://github.com/user-attachments/assets/6c34229f-8f82-4306-86c7-f4be615bb4dc)

<p>Click on Users and make sure that "Require registration and login to create tickets" is UNCHECKED.</p>

![image](https://github.com/user-attachments/assets/17aa31de-0c11-4a32-9494-08d1db4bce87)

<p>Configured osTickets to require registration and login to create tickets</p>
<hr>
<h3>Configured Agents Named John & Jane Doe</h3>

<p>5). Click the Agents section and click "Add New Agent". </p>

![image](https://github.com/user-attachments/assets/4b49ebbe-59eb-45b6-82a7-f1f139a8c913)

<p>Fill out the following information for the agent "John Doe"</p>

![image](https://github.com/user-attachments/assets/74d54587-9ba9-4841-aad6-73e45ae32088)

<p>Click on "Set Password" so we can set the password for John's account.</p>

![image](https://github.com/user-attachments/assets/5d2e103e-d2f1-4741-bc2d-4d608c9784e6)

<p>Uncheck all the boxes and set the password as "Password1". Click on update once you filled out John's password.</p>

![image](https://github.com/user-attachments/assets/e452138f-aacf-4349-a3aa-841cb64e2060)

<p>Next click on "Teams" and add John to the Level 1 Support Team. Make sure you press add before you click Save.</p>

![image](https://github.com/user-attachments/assets/5b41e9fc-aed2-4109-989c-21105bd3b13e)

<p>Next, we are going to create "Jane Doe". Click Agents and Add New.</p>

![image](https://github.com/user-attachments/assets/4b49ebbe-59eb-45b6-82a7-f1f139a8c913)

<p>Fill out the following information for Jane Doe.</p>

![image](https://github.com/user-attachments/assets/41a2f787-548e-49c8-b025-f8afdebe6a39)

<p>Click on "Set Password" so we can set the password for Jane's account.</p>

![image](https://github.com/user-attachments/assets/5d2e103e-d2f1-4741-bc2d-4d608c9784e6)

<p>Uncheck all the boxes and set the password as "Password1". Click on update once you filled out Jane's password.</p>

![image](https://github.com/user-attachments/assets/e452138f-aacf-4349-a3aa-841cb64e2060)

<p>Next click on Teams and add Jane to the "Online Banking" team. Make sure you press add before you click Save.</p>

![image](https://github.com/user-attachments/assets/4367e7bc-d11a-4961-a70b-61070302a27e)

<p>Now add Jane to the SysAdmins Department. Click on Agents and then Jane Doe. Click on Access.</p>

![image](https://github.com/user-attachments/assets/5c33d167-d29b-476c-818c-ff3fb39b9ca5)

<p>Next make her Primary Department SysAdmins and give her Supreme Admin. Then save your changes.p>

![image](https://github.com/user-attachments/assets/def49f93-0882-4e93-9438-9d8616a2148c)

<p>Created two agents named John & Jane Doe and added them to their teams/departments.</p>
<hr>
<h3>Configured Users Karen & Ken Doe</h3>

<p>6). Click on the Agent Panel and then Users</p>

![image](https://github.com/user-attachments/assets/98563d31-4022-40a1-8c23-1ba8c94efa9a)

<p>Click on Add User</p>

![image](https://github.com/user-attachments/assets/04c6b129-a505-4c21-8f65-93322204da96)

<p>Fill out the information for Karen Doe and then click Add User</p>

![image](https://github.com/user-attachments/assets/1851f145-7879-448c-a8e5-886d10b03b5a)

<p>Again click on Add User</p>

![image](https://github.com/user-attachments/assets/04c6b129-a505-4c21-8f65-93322204da96)

<p>Fill out the information for Ken Doe and then click Add User</p>

![image](https://github.com/user-attachments/assets/8756a047-123d-4c97-a356-fa728c9d9e1e)

<p>Created the users Karen and Ken so they can create tickets.</p>
<hr>
<h3>Configured SLA Rules</h3>

<p>7). Click on Admin Panel and select Manage.</p>

![image](https://github.com/user-attachments/assets/2415ae2e-5ff3-44d8-898e-a4568e105078)

<p>Select SLA and select Add New SLA Plan </p>

![image](https://github.com/user-attachments/assets/c0ab2750-e25d-46f6-8aa4-129a680c4b76)


<p>Fill out the SLA to have Sev-A [Grace Period - 1 Hour, Schedule - 24/7] Sev-B [Grace Period - 4 Hours, Schedule - 24/7] and Sev-C [Grace Period - 8 Hours, Schedule - Business Hours]. </p>

![image](https://github.com/user-attachments/assets/715d86f7-0125-4671-bf49-e7c3254e8cfc)

![image](https://github.com/user-attachments/assets/6a2bcfdc-d387-4768-a531-51fcd99bde4d)

![image](https://github.com/user-attachments/assets/623595a1-2a10-461f-9de6-1556d94a0c7d)

<hr>
<h3>Configured Help Topics For When Users Create A Ticket</h3>

<p>8). The final stpe is to configure the help topics to have the common topics for tickets you may resolve. </p>

<p>Click Help Topics under the Manage section. Then add new Help Topic. </p>

![image](https://github.com/user-attachments/assets/35eb0cbf-9982-484a-acd1-5732fcfffb09)

<p>Set the Help Topic to Businesss Critical Outage and Parent Topic to Report A Problem.</p>

![image](https://github.com/user-attachments/assets/d6849c91-5cd3-4e5c-b80e-816fa72efbbb)

<p>Create Help Topics for the following topics, Access Issue, Equipment Request, Other, Password Reset, and Personal Computer Issues all with the same Parent Topic "Report A Problem".</p>

![image](https://github.com/user-attachments/assets/7751fa56-5cde-4926-9609-209c226526ea)

<p>Created different help topics that are popular topics for ticket support to answer and categorize each type of ticket.</p>
<hr>

<p>Congratulations! You have successfully set up osTicket post installation.</p>
