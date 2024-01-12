<h1> SOC Analyst Home Lab </h1>

<h2>Description</h2>
This project involves setting up a small virtualization environment, putting on our adversary hat, generating and observing some noise. Emulating an adversary for crafting detections, blocking an attack, tuning false positives, and triggering YARA scans with detection rules.
<br />
<h2>For context</h2> 
I am using the free version of VMware Workstation, I set up Windows VM as is will all defaults, then i completely disabled windows defender on the windows VM. The Ubuntu Server i also set up as is with all defualts, but then configured the Ubuntu Server to have a static IP so no worrying about it changing in time.
<br />

<h2>Environments, Languages and Utilities Used</h2>

- <b> VMware Workstation </b> 
- <b> Windows VM </b>
- <b> Ubuntu Server 22.04.1 </b>
- <b> Sysmon </b>
- <b> LimaCharlie EDR </b>
- <b> YARA </b>

<h2>Program walk-through:</h2>

<p align="center">
Download and install VMware Workstation: <br/>
<img src="https://i.imgur.com/hEWffjt.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Download and deploy Windows VM:  <br/>
<img src="https://i.imgur.com/2yu5gKs.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Download and install Ubuntu Server: <br/>
<img src="https://i.imgur.com/Yg6IXV3.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Prevent Windows VM from going into standby:  <br/>
<img src="https://i.imgur.com/yJLNQqT.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
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
