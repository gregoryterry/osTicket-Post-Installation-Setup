# osTicket-Post-Installation-Setup
OsTicket post installation setup will create and configue admin and agent accounts, create departments and setup service level agreements.

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2></h2>

-
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1  (Configure Roles)
- Item 2  (Configure Departments)
- Item 3  (Create Teams and Agents)
- Item 4  (Configure SLAs "Service Level Agreements")
- Item 5  (Configure Help Topics)


<h2>Configuration Steps</h2>

<h4> A Summary of Roles</h4>

<p>Roles are the permissions granted to Agents according to the Departments that they have access to.  Each Role has a set of permissions that can be enabled or disabled depending on which role and departments an agent needs access to. 
<p>
<p>An unlimited number of roles can be created and assigned to Agents with access to various departments.
<p>

<h4>Role Permissions for Tickets include:</h4>
<p>Assign: Ability to assign tickets to agents or teams
<p>Close: Ability to close tickets
<p>Create: Ability to open tickets on behalf of users
<p>Delete: Ability to delete tickets
<p>Edit: Ability to edit tickets<p>
<p>Edit Thread: Ability to edit thread items of other agents<p>
<p>Link: Ability to link tickets
<p>Mark as Answered: Ability to mark a ticket as Answered/Unanswered
<p>Merge: Ability to merge tickets
<p>Post Reply: Ability to post a ticket reply
<p>Refer: Ability to manage ticket referrals
<p>Release: Ability to release ticket assignment
<p>Transfer Ability to transfer tickets between departments
<p>Role Permissions for Tasks include:
<p>Assign: Ability to assign tasks to agents or teams
<p>Close: Ability to close tasks
<p>Create: Ability to create tasks
<p>Delete: Ability to delete tasks
<p>Edit: Ability to edit tasks
<p>ost Reply: Ability to post task update
<p>Transfer: Ability to transfer tasks between departments
<p>

<h4>Item 1  (Configure Roles)</h4>

<p>In your web browser, enter this url “http://localhost/osTicket/scp/login.php”  to get to the Admin panel logon.
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Select the Admin Panel tab > Roles > Agents
</p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<h5>Add New Role</h5>

<p>Name: Supreme Admin >  add role
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Supreme Admin role was created
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Select the Supreme admin role > select the roles tab  >  select the Permissions tab > check all permissions
**This will grant all permissions to the Supreme Admin role
Save Changes
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Select the Supreme Admin role > Permissions tab  > Select the Tasks tab > make sure all boxes are selected > update
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Under the Permissions tab > select Knowledgebase > check the Premade box  > save changes
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<h4>Item 2  (Configure Departments)</h4>

<p>The next step is to configure departments for osTicket
<p>
<p>Select the Departments tab  > Add a new department
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Add the “System Administrators” department
<p>
<p>Select the following fields: when done > create department
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>The System Administrators department was created
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<h4>Item 3  (Create Teams and Agents)</h4>

<p>Select the Teams tab > Add New Team
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Name:  Level II Support
<p>
<img src="" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<p>Select the Members tab > Select an Agent > add  > Create Team
<p>
<img src="" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<p>Greg Terry is now a member of the Level II Support team
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>




<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
