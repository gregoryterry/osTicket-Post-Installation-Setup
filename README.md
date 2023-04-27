# osTicket-Post-Installation-Setup
OsTicket post installation setup will create and configue admin and agent accounts, create departments and setup service level agreements.

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2></h2>

-<h2>Environments and Technologies Used</h2>

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
 <p>
<img src="https://i.imgur.com/jpVbEbu.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>Select the Https://imgpile.com/images/h688Th.pnghe  > Admin Panel tab > Roles > Agents
</p>
<img src="https://imgpile.com/images/h68o7R.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="https://imgpile.com/images/h68AyN.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<h5>Add New Role</h5>

<p>Name: Supreme Admin >  add role
<p>
<img src="https://imgpile.com/images/h68BTL.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Supreme Admin role was created
<p>
<img src="https://imgpile.com/images/h68v7o.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Select the Supreme admin role > select the roles tab  >  select the Permissions tab > check all permissions
**This will grant all permissions to the Supreme Admin role
Save Changes
<p>
<img src="https://imgpile.com/images/h6VlkC.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Select the Supreme Admin role > Permissions tab  > Select the Tasks tab > make sure all boxes are selected > update
<p>
<img src="https://imgpile.com/images/h6Vorw.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Under the Permissions tab > select Knowledgebase > check the Premade box  > save changes
<p>
<img src="https://imgpile.com/images/h6VAUi.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<h4>Item 2  (Configure Departments)</h4>

<p>The next step is to configure departments for osTicket
<p>
<p>Select the Departments tab  > Add a new department
<p>
<img src="https://imgpile.com/images/h6VOkk.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Add the “System Administrators” department
<p>
<p>Select the following fields: when done > create department
<p>
<img src="https://imgpile.com/images/h6VvrX.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>The System Administrators department was created
<p>
<img src="https://imgpile.com/images/h6VEUE.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<h4>Item 3  (Create Teams and Agents)</h4>

<p>Select the Teams tab > Add New Team
<p>
<img src="https://imgpile.com/images/h6XTq8.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Name:  Level II Support
<p>
<img src="https://imgpile.com/images/h6Xhh3.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<p>Select the Members tab > Select an Agent > add  > Create Team
<p>
<img src="https://imgpile.com/images/h6Xtsi.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<p>Greg Terry is now a member of the Level II Support team
<p>
<img src="https://imgpile.com/images/h6XP24.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
 
<h4>How to Create Teams from a group of Agents</h4>

<p>Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter. Having Agents from different Departments assigned to a Team will supersede the parameters of the Agents’ Department rules. This will allow anyone to create tickets, registration will not be required to create tickets. Make sure require registration and login to create tickets is unchecked.

<p>Admin User Panel  > settings > users
<p>
<img src="https://imgpile.com/images/h6Xf3X.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
 
  
 <h4>Create Agents</h4>
 <p>Admin Panel > Agents > Add New Agent
<p>
  <img src="https://imgpile.com/images/h6Xf3X.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
  
  <p>Enter the agent’s name:  Jane Doe Email: jane.doe@osticket.com Username: jane.doe Set Password: Create
    <p>
    <img src="https://imgpile.com/images/h6XL61.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
    
      
<p>un-check, send the agent a password reset email and select set
  <p>
    <img src="https://imgpile.com/images/h6Xg2S.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
 
 <p>Select the Access tab **to set the departments and roles this agent will have access to.
    <p>
      <img src="https://imgpile.com/images/h6XE83.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
    
 <p>Select Permissions tab > check all selections
   <p>
     <img src="https://imgpile.com/i/h6XE83" height="70%" width="70%" alt="Disk Sanitization Steps"/>
 
 <p>Agent Jane Doe has been added
<p>
   <img src="https://imgpile.com/images/h6XacF.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
  
<p>The agent Jane Doe is a member of the Systems Administrators department.
 <p>
<img src="https://imgpile.com/images/h6H4Mk.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
  
  
<h4>How to Reset an agent’s password</h4>

<p>If necessary, administrators can manually reset an agent’s password by clicking the Set Password box in the middle of the Account page. This will produce a pop-up box with two options; the first is to send a password reset email to the agent. Please note, if the agent has not first set a password post-creation they can not reset said password. The second option for the admin is to uncheck the box which will populate fields to manually set a password for the agent. Once manually set, the admin will need to communicate this to the agent allowing them to log-in; the agent can be forced to reset the password upon logging in by keeping the box checked at the bottom left of the pop-up.
<p>
 <img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>
 
 <p>Reset Agent Password manually
  <p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>
 
  <h4>User Directory</h4>
<p>Agent panel > users > user directory > add user
 <p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

  <img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>
 
<p>Here is the new user, John Smith.  John can create a ticket by selecting create a new ticket at the bottom right.
<p>
 <img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>
 

<h4>Item 4  (Configure SLAs "Service Level Agreements")</h4>


<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

      <h4>Create three SLA plans</h4>
      
        <P>Add new SLA plan
        <p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Name: SEV-A Grace period: 1hr Schedule: 24/7  >  Add plan
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>The new SLA is created, repeat the procedure for SEV-B and SEV-C
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>I created  SEV-B and SEV-C using the same procedure I used to create SEV-A
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<P>Name: SEV-B Grace period: 4hr Schedule: 24/7  >  add plan
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>SEV-C Grace period: 8hr Schedule:  Monday - Friday 8a - 5p with US holidays >  add plan
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Here are the three new SLAs
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>


<h4>Configure Help Topics</h4>

<p>These are the default help topics
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>I will create the following help topics

  Business Critical Outage
  Personal Computer Issues
  Equipment Request
  Password Reset
<p>

<p>To add a new help topic

   Admin Panel -> Manage -> Help Topics > Add New Help Topic
   <p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>The new help topic should look like this
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<P>When completed you should have four new help topics
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>osTicket post installation setup is now complete.  I will continue to the next lab, "Tickets and Ticket Lifecycle"
<p>


<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

