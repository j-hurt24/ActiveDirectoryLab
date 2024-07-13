<h1>Active Directory Lab</h1>

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows Server 2019 (Domain Controller) </b>
- <b>Windows 10 (Target Machine) </b>
- <b>Ubuntu Server 22.04 (Splunk Server)
- <b>Kali Linux (Adversary) </b>

<h2>Program walk-through:</h2>

<p align="center">
Topography of Network <br/>
<img src="https://imgur.com/xwz5mHL" height="80%" width="80%" alt="Topography"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://imgur.com/a/CtodmdK" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
