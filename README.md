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

- Configure roles
- Configure departments
- Configure teams
- Configure agents
- Configure users
- Configure SLA
- Configure help topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/ZHnDKEV.png" width="80%" alt="Disk Sanitization Steps"/>
<p>
1. Configure Roles:
 <br>
-Admin Panel -> Agents -> Roles
 <br>
-Supreme Admin *enable all permissions 
</p>
<br />

<p>
<img src="https://i.imgur.com/ZEv2XAr.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Configure Departments:
<br>                                                                                    
-Admin Panel -> Agents -> Departments: System Administrators                                                                     
</p>
<br />

<p>
<img src="https://i.imgur.com/clV4ObT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Configure Teams:
  <br>                                                                                                
-Admin Panel -> Agents -> Teams
  <br>                                                                                                
-Level I Support 
  <br>                                                                                               
-Level II Support
</p>
<br />
                                                                                                 
<p>
<img src="https://i.imgur.com/8NKG53S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Allow anyone to create tickets:
   <br>                                                                                               
-Admin Panel -> Settings -> User Settings 
   <br>                                                                                               
-Registration Required: check "Require registration and login to create tickets" 
</p>
<br />

<p>
<img src="https://i.imgur.com/1srDNSn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Configure Agents (workers):
  <br>
-Admin Panel -> Agents -> Add New: Jane, John
</p>
<br />

<p>
<img src="https://i.imgur.com/5mrmRSa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Configure Users (customers):
  <br>
-Agent Panel -> Users -> Add New: Karen, Ken
</p>
<br />

<p>
<img src="https://i.imgur.com/hhXR9U4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Configure SLA:
  <br>
-Admin Panel -> Manage -> SLA
  <br>
-Sev-A (1 hour, 24/7)
  <br>
-Sev-B (4 hours, 24/7)
  <br>
-Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://i.imgur.com/vBeIFGl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Configure Help Topics:
-Admin Panel -> Manage -> Help Topics
  <br>
-Business Critical Outage
  <br>
-Personal Computer Issues
  <br>
-Equipment Request
  <br>
-Password Reset
</p>
<br />
