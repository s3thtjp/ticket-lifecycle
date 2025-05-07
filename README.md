<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/pk8xsm7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First we'll need to log in to osTicket as the Admin by entering the correct credentials. 
</p>
<br />

<p>
<img src="https://i.imgur.com/5Vm5ILx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we need to delete the "Maintenance" department. When users send tickets by default it gets sent to this department and we want it to go to "Support". To do this we need to be under the "Admin Panel" and select the top "Agents" tab then "Departments" then click on the box next to "Maintenance" the click the drop down menu next to "More" on the right and select "Delete" then click on the "Yes, Do It" button. 
</p>
<br />

<p>
<img src="https://i.imgur.com/F6MpVuF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we are going to be acting like an end-user sending in a ticket stating "Hi there. I just came back from a two-week vacation and now I can't log into my computer. It says my password is expired. I think I remember getting an email about changing my password before I left, but I forgot to do it. Can you help me get back into my account? My username is MThompson." To do this we have to open a new tab in the web broswer and go to <a href="http://localhost/osTicket">HERE</a> and click on the "Open a New Ticket" button. Then we will fill in the ticket as "Karen" from the osTicket configuration set up. When finished click on the "Create Ticket" button to submit the ticket. 
</p>
<br />

<p>
<img src="https://i.imgur.com/O4tot3i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we are going to be logging on as "John" to view the ticket and see if there are any changes that needs to be made to Karen's ticket. To do this we need to log out of the "adminuser" and enter the credentials for john's account. When logged in we can only view the ticket but not make any changes. So let's fix that by logging out as "john" and back into the "adminuser". 
</p>
<br />

<p>
<img src="https://i.imgur.com/abb5MPm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As "adminuser" we need to fix where John can now make changes to the tickets. We do this by clicking on the "Agents" tab at the top then selecting "John Doe" then we go to the "Access" tab and under primary department in the select department we'll select "Support" if not already selected and change the role to "Supreme Admin" then select the "Save Changes" at the bottom. Next we will log out of "adminuser" and back into "john".
</p>
<br />

<p>
<img src="https://i.imgur.com/ual0mhi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once logged back in as John we can now make changes to the ticket including changing help topic, assigning the ticket and changing the SLA Plan. To make these changes click on the links and select the appropriate choices. 
</p>
<br />

<p>
<img src="https://i.imgur.com/zdouN4P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Look "John" has resolved the issue by resetting the password and gave the customer a temporary password. The ticket is now finished and ready to be resolved.
</p>
<br />

