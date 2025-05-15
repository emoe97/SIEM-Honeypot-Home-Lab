# SIEM-Honeypot-Home-Lab
<h2>Failed RDP to IP Geolocation Information</h2>


 ### [YouTube Demonstration](https://www.youtube.com/watch?v=nYCqmv3kXgY)


<h2>Description</h2>
<b> In this lab, I created a Honeypot using Microsoft Azure to trap cybercriminals and log the geolocation of the attacker on a world map. 
</b>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API
<br />
<br />
Create A Virtual Machine within Microsoft Azure.
<p align="center">
<img src="https://i.imgur.com/xtwNPvQ.png"(https://i.imgur.com/xtwNPvQ.png) alt="Create Virtual Machine within Microsoft Azure"/>
</p>
<br />
<br />
<b> Once the virtual machine is created, next step is to log into virtual machine by using the Windows RDP (Remote Desktop) application. 
</b>
<p align="center">
<img src="https://i.imgur.com/ZSG8kuB.png"(https://i.imgur.com/ZSG8kuB.png) alt="Once the virtual machine is created, next step is to log into virtual machine by using the Windows RDP (Remote Desktop) application"/>
</p>
<h2>Attacks from China coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/qaWjV2c.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/krRFrK5.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
