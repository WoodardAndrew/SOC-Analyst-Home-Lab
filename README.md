<h1> SOC Analyst Home Lab </h1>

<h2>Description</h2>
This project involves setting up a small virtualization environment, putting on our adversary hat, generating and observing some noise. Emulating an adversary for crafting detections, blocking an attack, tuning false positives, and triggering YARA scans with detection rules.
<br />
<h2>For context</h2> 
I am using the free version of VMware Workstation, I set up Windows VM as is will all defaults, then i completely disabled windows defender on the windows VM. The Ubuntu Server i also set up as is with all defaults, but then configured the Ubuntu Server to have a static IP so no worrying about it changing in time.
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
<img src="https://i.imgur.com/XXNhAM8.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/3TEf2rc.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Ubuntu Server: <br/>
<img src="https://i.imgur.com/6dqUCwA.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/Sd40w7K.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/n2mZGUs.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Setting Static IP: <br/>
<img src="https://i.imgur.com/oR0RSmB.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/gMM5EnX.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/nQPiZG6.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/UzZGiTq.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Disabling Defender on Windows VM:  <br/>
<img src="https://i.imgur.com/9NxKVaJ.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/w9J2sif.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/NcK0x3Z.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/6Ud7mhO.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/2ExYGNv.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Prevent Windows VM from going into standby:  <br/>
<img src="https://i.imgur.com/EVkSRsm.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Installing Sysmon on Windows VM:  <br/>
<img src="https://i.imgur.com/4pyGKt1.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Installing LimaCharlie EDR on Windows VM:  <br/>
<img src="https://i.imgur.com/CoJ0EZq.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/FpZvfYB.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/8hlUzTg.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/tto9ayD.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/TezGiAn.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/fBuXbMG.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/Dnuun7c.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/8xRDmX3.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Configuring LimaCharlie to ship Sysmon Event Logs alongside its own EDR telemetry:  <br/>
<img src="https://i.imgur.com/YBT4X6S.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
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
