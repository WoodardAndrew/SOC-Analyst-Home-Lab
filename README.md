<h1> SOC Analyst Home Lab </h1>

<h2>Description</h2>
This project involves setting up a small virtualization environment, putting on our adversary hat, generating and observing some noise. Emulating an adversary for crafting detections, blocking an attack, tuning false positives, and triggering YARA scans with detection rules.
<br />
<h2>For context</h2> 
I am using the free version of VMware Workstation, I set up Windows VM as is with all defaults, then i completely disabled windows defender on the windows VM. The Ubuntu Server i also set up as is with all defaults, but then configured the Ubuntu Server to have a static IP so no worrying about it changing in time.
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
<img src="https://i.imgur.com/bgzqnsL.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/Sf3oHw9.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Setting Up Attack System:  <br/>
<img src="https://i.imgur.com/qsROW2x.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/DkKeLkk.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Generating C2 Payload:  <br/>
<img src="https://i.imgur.com/KALgere.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/aZWDqJz.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br /> 
Starting Command and Control Session:  <br/>
<img src="https://i.imgur.com/chdutYr.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/hVK3384.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/2IkE4P6.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/s2iM5do.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/NIh4KSL.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Observing EDR Telemetry:  <br/>
<img src="https://i.imgur.com/qaWnUfQ.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/Br7rOUw.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/LVK9WBK.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/xSz2mkl.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/nOB5LsB.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/cFCtmHj.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/iuaFKZu.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Getting Adversarial:  <br/>
<img src="https://i.imgur.com/6CRVYXw.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Detecting The Credential Dump:  <br/>
<img src="https://i.imgur.com/06JxGjb.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Crafting Detection and Response Rule:  <br/>
<img src="https://i.imgur.com/QYKzytr.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/V2W6stZ.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/caj26is.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Testing Detection and Response Rule:  <br/>
<img src="https://i.imgur.com/NvWF5XK.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/ZhlZzqV.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Blocking Attacks:  <br/>
<img src="https://i.imgur.com/nbjBe2l.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/pom4Jz4.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/7guTH2F.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/DHwSuen.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/17GwHdK.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/8Jc3cxR.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Automating YARA Scanning:  <br/>
<img src="https://i.imgur.com/j9vBfwk.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/YlUoOEG.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/EOXqWKV.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/Q7zYEnr.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/4Obox8V.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/DA21za5.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/2N2rCPK.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Testing YARA Signature:  <br/>
<img src="https://i.imgur.com/jSMjooR.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/Xycdnyp.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Automating YARA to scan downloaded EXEs:  <br/>
<img src="https://i.imgur.com/dWDDn9Y.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/ZYH2r6J.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<br />
<br />
Automating YARA to scan processes launched from Downloads directory:  <br/>
<img src="https://i.imgur.com/MbBKA24.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
<img src="https://i.imgur.com/c2lW8Mp.png" height="80%" width="80%" alt="SOC Analyst Home Lab"/>
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
