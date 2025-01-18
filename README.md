<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Windows App for Mac (previously named Microsoft Remote Desktop)
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<br />
<p>
  Admin Panel -> Agents -> Roles.
</p>
<p>
  Supreme Admin:
</p>
<p>
  <img src="https://i.imgur.com/LnUrH1p.png" height="75%" width="100%" alt="Definitions"/>
  <img src="https://i.imgur.com/2lakdaI.png" height="75%" width="100%" alt="Permissions"/>
  <img src="https://i.imgur.com/XNhjXw5.png" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://i.imgur.com/hV7jIUZ.png" height="75%" width="100%" alt="Even More Permissions"/>
  <img src="https://i.imgur.com/aJSPGKA.png" height="75%" width="100%" alt="Sys Admin Success"/>
</p>
<br />
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>
  Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
  <img src="https://i.imgur.com/7hclTh2.png" height="75%" width="100%" alt="System Administrators"/>
</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
  Online Banking:
</p>
<p>
  <img src="https://i.imgur.com/p97HhHH.png" height="75%" width="100%" alt="Level II Support"/>
</p>
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
  Admin Panel -> Settings -> User Settings.
</p>
<p>
  Make sure "Require registration and login to create tickets" is not selected:
</p>
<p>
  <img src="https://i.imgur.com/lcw84SF.png" height="75%" width="100%" alt="ticket creations"/>
</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  Jane Doe:
</p>
  <img src="https://i.imgur.com/Dy9IQ2D.png" height="75%" width="100%" alt="agent one access"/>
  <img src="https://i.imgur.com/3xeDxGt.png" height="75%" width="100%" alt="agent one access"/>
<p>
  John Doe:
</p>
<p>
  <img src="https://i.imgur.com/TAbzVHj.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://i.imgur.com/Izdeo8Q.png" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  ken:
</p>
  <img src="https://i.imgur.com/w3XoMLn.png" height="75%" width="100%" alt="user access"/>
<p>
  karen:
</p>
  <img src="https://i.imgur.com/Q9oMIiJ.png" height="75%" width="100%" alt="user access"/>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://i.imgur.com/TxtpToT.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://i.imgur.com/gM0BZFa.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://i.imgur.com/OWJQFqy.png" height="75%" width="100%" alt="sev three"/>
</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
<br />
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  Other.
</p>
  <img src="https://i.imgur.com/IZpXV72.png" height="75%" width="100%" alt="business critical outage"/>
  <img src="https://i.imgur.com/HdtlvON.png" height="75%" width="100%" alt="personal computer issues"/>
  <img src="https://i.imgur.com/hfaK4lf.png" height="75%" width="100%" alt="equipment request"/>
  <img src="https://i.imgur.com/Ersvju6.png" height="75%" width="100%" alt="password reset"/>
  <img src="https://i.imgur.com/Kh7dO3w.png" height="75%" width="100%" alt="other"/>
</p>
<br />
<br />
<p>
  This now fully configures our osTicket. I hope this guide was able to help clarify and assist you in setting up your osTicket. It is recommended to practice triaging and solving tickets.
</p>
<p>
  This is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.
</p>
