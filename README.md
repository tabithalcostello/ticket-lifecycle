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

- Windows 10</b> 

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p align="center">
<img src="https://i.imgur.com/U8VPRJw.png" height="50%" width="50%" alt="Customer Login"/>
</p>
<p> In the osTicket's Support Center webpage for users (http://localhost/osTicket/), click on Open a New Ticket. Log in as user (Karen Hart) created in the previous tutorial. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/pPA9DT1.png" height="50%" width="50%" alt="Intake of Ticket"/>
</p>
<p> Karen selects the Help Topic: Business Critical Outrage and provides a brief summary that customers are complaining about not being able to access their mobile bank account. When finish, she selects to Create Ticket.
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/Dc1cGZM.png" height="50%" width="50%" alt="Ticket Receive"/>
</p>
<p> In the osTicket for agents (http://localhost/osTicket/scp/login.php), the administrator (Jane Doe) created in the previous tutorial logs in. In the Agent Panel, select Tickets. Click on Karen's ticket. In a short message, Jane notifies Karen that there is already someone addressing that issue. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/IoCSvxF.png" height="50%" width="50%" alt="Changing Default Settings"/>
</p>
<p> In the top portion of the ticket, Jane addresses the Default settings. Priority changes from Normal to Emergency. SLA from Default to SEV-A. SLA SEV-A sets the grace period for 1 hour 24/7.
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/eCqui2w.png" height="50%" width="50%" alt="Resolve Issue"/>
</p>
<p> After the issue had been fixed, Jane sends a message informing Karen that the issue has been resolved. Jane changes the Ticket Status from Open to Resolved, which will close out the ticket. The closed ticket no longer will appear on the Open tickets section. Closed tickets can be accessed in the Tickets section titled Closed. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/RlLUVOG.png" height="50%" width="50%" alt="Check Ticket Status"/>
</p>
<p> Karen can review Jane's response by returning to the osTicket website and click on Check Ticket Status. This will require her e-mail address and ticket number. A link will be sent to her e-mail. Or, Karen can log into osTicket and click Closed to pull up the ticket.  
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/eMoqqSF.png" height="50%" width="50%" alt="Agent Ticket"/>
</p>
<p> Jane receives a phone call that a field supervisor needs a new MIFI. As a way to track the external request, Jane creates a ticket. In the agent's osTicket webpage, Jane creates a New Ticket. In Tickets, click New Tickets. Jane lists herself as the user. Next to Ticket Notice change to Do Not Send Alert. In the Help Topic, select Equipment Request. For Department, choose Support. For the SLA Plan, select SEV-B. SLA SEV-B sets the grace period for 4 hours in a 24/7 time frame. In the Assign to, Jane assigns it to herself. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/9majzws.png" height="50%" width="50%" alt="Self Ticket"/>
</p>
<p> Jane treats the ticket as if she was the customer by filling out the message. Jane includes the reason for issuing out the equipment and how it will be handled. In the Internal Notes, Jane logs the MIFI's serial and phone number, then changes the Ticket Status to Resolve.
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/r4gqO2M.png" height="70%" width="70%" alt="Poor Ken"/>
</p>
<p> In the OsTicket's Support Center webpage, Ken (user) creates a ticket for Password Reset. Jane accesses the ticket. Jane changes the default settings for Priority's Normal to Low. SLA from Default to SEV-C. SLA SEV-C sets the grace period for 8 hours on a business schedule of Monday-Friday 8am to 5pm with US holidays. Jane responds to Ken message on how the issue will be addressed. Jane has access to the Active Directory and sets Ken's password to be changed on next login. Jane selects the Ticket Status as Resolved. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/FF3maz0.png" height="50%" width="50%" alt="Bye"/>
</p>
<p> align="center" This is the end of osTicket Lifecycle. 
</p>
<br />
