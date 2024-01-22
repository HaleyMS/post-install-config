<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This page outlines the post-install configuration of my open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

https://i.imgur.com/uo8wJky.mp4

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1: Role Configurations
- Item 2: Team Configurations
- Item 3: Agent and Client Configurations
- Item 4: SLA Configurations
- Item 5: Help Topic Configurations

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/EjvGOHF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I started with adding a Supreme Administrative role.   
</p>
<br />

<p>
<img src="https://i.imgur.com/OJOxPMT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created a level two support team.
</p>
<br />

<p>
<img src="https://i.imgur.com/zuf8DPM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/XDWpOKw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The images above shows me configuring one two agent roles and one of two client roles. The Agent named Jane was given the Supreme Admin role shown above. I also created Ken and Karen and registered their accounts for use.
</p>
<br />
<p>
<img src="https://i.imgur.com/AVSK62g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the image above I configured the SLA. I added a SEV-A with a grace period of 1 hour on a 24/7 schedule, SEV-B with a grace period of 4 hours on a 24/7 schedule, and SEV-C with a grace period of 8 hours with a regular work week schedule.   
</p>
<br /><p>
<img src="https://i.imgur.com/CrTB9aF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I am configuring the help topics.
