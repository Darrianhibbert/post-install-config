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

- Configure Roles (for grouping permissions) 
- Configure Departments (Ticket Visibility)
- Configure Agents
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/2Uc4qaM.png"/>
</p>
<p>Created a Supreme Admin role in osTicket, granting full access permissions within the admin panel to a designated agent for complete system control.
</p>
<br />

<p>
<img src="https://i.imgur.com/TvhURFa.png"/>
</p>
<p>Created a SysAdmins department in osTicket to enable top-level ticket visibility and streamlined issue management.</p>
<br />

<p>
<img src="https://i.imgur.com/URxgQ6E.png"/>
</p>
<p>Configured SLA For three different categorized cases sev-a to sev-c depeending on the impact and severity of the issue sit can be solved in 1 hour, 4 hours or in 8 hours within business hours only</p>
<br />

p>
<img src="https://i.imgur.com/3IdGhPM.png"/>
</p>
<p>Configured SLA policies in osTicket for three case categories (Sev-A to Sev-C) based on issue severity and impact, ensuring resolution within 1, 4, or 8 business hours.</p>
<br />
