<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
 This is the continuation of the previous tutorial. In this tutorial we will be configuring all the specfic roles, teams, agents, etc in order to actual create experiences with osTicket.
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/6d3e5947-87bc-4b61-a7a9-5c54cae552be" height="80%" width="80%" alt="Login"/>
</p>
<p>
The first step is to go into the login, and use the admin credentials from the previous tutorial
  <ul>
    <li><a href="http://localhost/osTicket/scp/login.php">This is the link to the login page.</a></li>
</ul>
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/0b5956e9-efd5-44c3-b066-82743a1b6831)" height="80%" width="80%" alt="Admin Panel"/>
</p>
<p>
At the top right click the "Admin Panel".
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/52174c67-081e-49a0-8962-41ff9b0568d5" height="80%" width="80%" alt="Navigation"/>
</p>
<p>
Next, head over to Agents > Roles > Add New Role
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/49098838-eb34-45e7-8dac-5ebb715c69cf" height="80%" width="80%" alt="New Role"/>
</p>
<p>
When adding the role, name the role "Supreme Admin" and allow all permissions. Once that is done select "Add Role".
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/018778ed-bdcc-4d2d-960e-8caaf082d2de" height="80%" width="80%" alt="Department"/>
</p>
<p>
Now go to the Deparments tab and select "Add New Department".
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/d83fba74-f82f-4e4a-879d-a4d44eb4b19c" height="80%" width="80%" alt="Sys Admin"/>
</p>
<p>
Input the name "System Administrators" and select "Create Dept".
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/6a7adad3-8417-4245-a1bc-5e39a5a4edee" height="80%" width="80%" alt="Team"/>
</p>
<p>
Go to "Teams" tab > Select "Add New Team".
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/0f3bf2f1-f95d-4625-aaad-66a23e4e196f" height="80%" width="80%" alt="Create"/>
</p>
<p>
Type "Level II Support" in the "Name" tab and select "Create Team".
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/9f56e325-c8b2-43c5-9f79-a4002aca7cc1" height="80%" width="80%" alt="User"/>
</p>
<p>
 Now, head to "Settings" > Users > Registration Required: Unchecked > Registration Method: Public > Select Save Changes.
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/97af1f1c-407c-4e23-82de-700f5e7bed2f" height="80%" width="80%" alt="Agents"/>
</p>
<p>
Go to "Agents" tab > Select "Add New Agent".
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/cb57a6b6-99ab-4a19-8f9e-9200ee7806d0" height="80%" width="80%" alt="New Agents"/>
</p>
<p>
 Create these accounts in order:
 <ol>
  <li>Name: Jane Doe</li>
  <li>Email Address: jane.doe@osticket.com</li>
  <li>Username: jane.doe</li>
  <li>Set the password to "Password2"</li>
  <li>Go to Access and set the department to SysAdmins and select Supreme Admin for the role.</li>
  <li>Go to the teams section and select Level II Support, then create.</li>
</ol>
Repeat these steps to create a new account with the name "John Doe"
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/6300efca-8681-4ba8-b749-b41b1fcc0be2" height="80%" width="80%" alt="New User"/>
</p>
<p>
Now, Select Agent Panel > Users > Add User
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/c3838a86-bc42-4dc3-a3c5-72a12b43b6e8" height="80%" width="80%" alt="Create"/>
</p>
<p>
Create these accounts:
 <ul>
  <li>Email Address: ken@osticket.com</li>
  <li>Full Name: Ken Ken</li>
  <li>Email Address: karen@osticket.com</li>
  <li>Full Name: Karen Karen</li>
</ul>
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/027b854f-2d9b-4892-8cf6-1e6cdf208b6b" height="80%" width="80%" alt="SLA"/>
</p>
<p>
Head back to "Admin Panel" > Manage > SLA > Select "Add New SLA Plan".
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/454aa81d-0ca1-458e-bf04-41f2bd9fd6ae" height="80%" width="80%" alt="SLA Plan"/>
</p>
<p>
Add these three SLA's
 <ul>
  <li>SEV-A with a grace period of 1 hour, and a 24/7 schedule</li>
  <li>SEV-B with a grace period of 4 hours, and a 24/7 schedule</li>
  <li>SEV-C with a grace period of 8 hours, and a Mon-Fri business hours schedule</li>
</ul>
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/a5a2688f-28a9-4b20-9d3c-9d3c2eb9f3f1" height="80%" width="80%" alt="Help Topics"/>
</p>
<p>
Go to Manage > Help Topics > Select "Add New Help Topic"
</p>
<br />

<p>
<img src="https://github.com/sebbec31/post-install-config/assets/125160491/49c49ffe-59ee-4e92-a1a6-33ae7a311e94" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add these four Help Topics:
 <ul>
  <li>Business Critical Outage</li>
  <li>Personal Computer Issues</li>
  <li>Equipment Request</li>
  <li>Password Reset</li>
</ul>
</p>
<br />
