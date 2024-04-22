<h1>Failed RDP to IP Geolocation Information</h1>


 ### YouTube Demonstration 


<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third-party API to collect geographic information about the attackers' location.
</b>
<br />
<br />
The script is used in this demo where I set up Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
Look up the attackers' Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />

![api key](https://github.com/sakhilesk/Sentinel-Lab/assets/89784327/b43f91de-4633-4407-9d74-01e5b994b8b1)
<p align="center">
<h1 RDP event fail logs to iP Geographic information"/>
</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from all over the world coming in; Custom logs being output with geodata</h2>

![Powershell log](https://github.com/sakhilesk/Sentinel-Lab/assets/89784327/ce31f142-8dab-4529-88ad-03c1eae4430f)

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

![Sentinel](https://github.com/sakhilesk/Sentinel-Lab/assets/89784327/d0421cdd-abf1-43f8-ba4f-d5799bcc6291)

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
