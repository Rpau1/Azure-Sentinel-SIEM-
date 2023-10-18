# Azure-Sentinel-SIEM-
Configured Azure Sentinel(Microsoft's cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to physical location and magnitude of attack.




<h2>Description</h2>
-The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.


-The script is used in this demo where, I setup Azure Sentinel (SIEM) and connect it to a live virtual machine in Azure acting as a Honeypot. 
-Observed live attacks (RDP Brute Force) from all around the world. 
-Used The powershell script and Kusto Query Language (KQL) to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!

map after 24hrs:
![sentinel final map](https://github.com/Rpau1/Azure-Sentinel-SIEM-/assets/147562929/69fcb4a5-9bd1-44b2-bd66-8e357b090860)


<br />


<h2>Languages Used</h2>

- <b>PowerShell: Extract RDP failed logon logs from Windows Event Viewer</b> 


<h2>Utilities Used </h2>

- <b>ipgeolocation.io: IP Address to Geolocation API</b>

<h2> Resources Used </h2>
<b>[YouTube: SIEM Tutorial] (https://youtu.be/RoZeVbbZ0o0?si=YNdqQ7tfGzRDojno)</b>

<b>*using the sentinel map querry script you can bypass the manual extraction proccess.</b> 

