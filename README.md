# Azure-Sentinel-SIEM-
Configured Azure Sentinel(Microsoft's cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to physical location and magnitude of attack.




<h2>Description</h2>
The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.

The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!

![sentinel final map](https://github.com/Rpau1/Azure-Sentinel-SIEM-/assets/147562929/69fcb4a5-9bd1-44b2-bd66-8e357b090860)


<br />


<h2>Languages Used</h2>

- <b>PowerShell: Extract RDP failed logon logs from Windows Event Viewer</b> 


<h2>Utilities Used </h2>

- <b>ipgeolocation.io: IP Address to Geolocation API</b> 


 
# text in gray
@@ text in purple (and bold)@@
```
--!>
