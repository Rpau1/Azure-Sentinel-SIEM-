# Azure-Sentinel-SIEM-
Configured Azure Sentinel(Microsoft's cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to physical location and magnitude of attack.




<h2>Description</h2>
The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.

The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />


<h2>Languages Used</h2>

- <b>PowerShell: Extract RDP failed logon logs from Windows Event Viewer</b> 


<h2>Utilities Used </h2>

- <b>ipgeolocation.io: IP Address to Geolocation API</b> 

<h2> Lab walk-through:</h2>

<p align="center">
S1: open free azure account (free for first $200 than would stop unless permited otherwise) <br/>

<br />
<br />
S2:once in the portal search up and select virtual machine <br/>

<br />
<br />
S3: Configure the machine according to picture <br/>
<img src="<blockquote class="imgur-embed-pub" lang="en" data-id="3ergk3X"><a href="https://imgur.com/3ergk3X">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script> height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
