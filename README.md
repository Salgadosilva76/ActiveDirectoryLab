<h1>Active Directory Home Lab 🌐</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description 📋</h2>

In this video, we’re going to walk through how to create an active directory home lab environment using Oracle virtual box. Configuring and running this lab will definitely help develop your understanding of how active directory and Windows networking works, so I’d like highly recommend running through it a couple times, ask questions where stuff isn’t clear, and eventually try to build it on your own without watching. Please let me know if you have any questions.
<br />


<h2>Languages and Utilities Used 💬</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used 💻</h2>

- <b>Windows 10</b> (21H2)
- Server 2019
<h2>Program walk-through: 🗒 </h2>

<p align="center">
Project Overview: <br/>
<img src="https://i.imgur.com/arcyoO2.png" height="80%" width="80%" alt="Project Overview"/>
<br />
<br />
Set up a new Virtual Machine:  <br/>
<img src="https://i.imgur.com/vJfTJU9.png" height="80%" width="80%" alt="Start a New Virtual Machine"/>
<br />
<br />
Install Server 2019 ISO: <br/>
<img src="https://i.imgur.com/1kXLovA.png" height="80%" width="80%" alt="Install Server 2019 ISO"/>
<br />
<br />
Assign IP Adress to Internal Network:  <br/>
<img src="https://i.imgur.com/ubiwxUG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up Active Directory Domain Services:  <br/>
<img src="https://i.imgur.com/hGagApt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Specify The Domain:  <br/>
<img src="https://i.imgur.com/6mQyglw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create an Organizational Unit:  <br/>
<img src="https://i.imgur.com/tTNfylI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Remote Access:  <br/>
<img src="https://i.imgur.com/WGR61ph.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up NAT for Connection:  <br/>
<img src="https://i.imgur.com/0owmIzc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up DHCP Server:  <br/>
<img src="https://i.imgur.com/bE0FNXw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure a New Scope:  <br/>
<img src="https://i.imgur.com/yDoLZey.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up IP Address for New Scope:  <br/>
<img src="https://i.imgur.com/cIBqXcK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Download File From Online Link:  <br/>
<img src="https://i.imgur.com/aXidBRI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open file and Run It as a Powershell script:  <br/>
<img src="https://i.imgur.com/EAQyKE5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run Powershell Script & Add Users:  <br/>
<img src="https://i.imgur.com/bQsq2xu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up Window 10 on a New VM:  <br/>
<img src="https://i.imgur.com/ZZfgHxN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open Command Line and Check IP Configurations On New VM:  <br/>
<img src="https://i.imgur.com/A4axvOc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up a Router on the DHCP:  <br/>
<img src="https://i.imgur.com/RD9r4OO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Restart DHCP on Domain Controller:  <br/>
<img src="https://i.imgur.com/4j59mK2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use "ipconfig /renew" on Client VM:  <br/>
<img src="https://i.imgur.com/wacin8h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ping to "www.google.com" to Test Connection:  <br/>
<img src="https://i.imgur.com/Qo7cZ5y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Rename The Computer and Join it to the DC Domain:  <br/>
<img src="https://i.imgur.com/uq9JyqG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
ERASEEEEE:  <br/>
<img src="https://i.imgur.com/uq9JyqG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
ERASEEEEEE:  <br/>
<img src="https://i.imgur.com/uq9JyqG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
