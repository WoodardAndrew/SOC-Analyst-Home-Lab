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

<h2>SOC Analyst Home Lab:</h2>

<p align="center">
VMware Workstation: <br/>
<img src="https://i.imgur.com/hEWffjt.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Windows VM:  <br/>
<img src="https://i.imgur.com/2yu5gKs.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Ubuntu Server: <br/>
<img src="https://i.imgur.com/6dqUCwA.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Setting Static IP: <br/>
<img src="https://i.imgur.com/Akqcr1X.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/1l3WR6T.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Disabling Defender on Windows VM:  <br/>
<img src="https://i.imgur.com/4DSMuYs.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/MxKxrZ5.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/V65L1pn.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Prevent Windows VM from going into standby:  <br/>
<img src="https://i.imgur.com/yJLNQqT.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Installing Sysmon on Windows VM:  <br/>
<img src="https://i.imgur.com/r2P1mJY.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Installing LimaCharlie EDR on Windows VM:  <br/>
<img src="https://i.imgur.com/SVuoM2L.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Setting Up Attack System:  <br/>
<img src="https://i.imgur.com/YBT4X6S.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
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
