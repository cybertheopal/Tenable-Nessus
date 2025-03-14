<h1>Tenable Nessus - Vulnerability Management on Windows</h1>

 ### [YouTube Demonstration](_________________)

<h2>Description</h2>
I will be showing you how to use Nessus on Azure with on a Windows 11 computer running a Virtual Machine. We will also change the configurations of the update plugin and component frequency to daily, ensuring the VM ports are open and firewalls are disabled, and credential vs non credential scans.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Vmware Fusion</b> 
- <b>Tenable Nessus (ubuntu)</b>

<h2>Environments Used </h2>

- <b>Linux</b> (Kali)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://imgur.com/gfLahy1.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
Install the program:  <br/>
<img src="https://imgur.com/Uz43yiT.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
Register and activate your account: <br/>
<img src="https://imgur.com/2BGoHyr.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
<br />
Install additional updates:  <br/>
<img src="https://imgur.com/jNqdsXS.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
Using command "ip addr" we are able to find our internal network:  <br/>
<img src="https://imgur.com/4z0r2Gu.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
Enure virtual machine is responding:  <br/>
<img src="https://imgur.com/YkrDGJU.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
and reciving ping:  <br/>
<img src="https://imgur.com/hTgKgNB.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
Setting up Nessus to run a basic network scan without credentials:  <br/>
<img src="https://imgur.com/j7lixvv.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
Update the settings:  <br/>
<img src="https://imgur.com/OXumoDp.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
Result of our virtual machine's vulnerability:  <br/>
<img src="https://imgur.com/U7GKUUI.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
Adding the credentials of our virtual machine into Nessus:  <br/>
<img src="https://imgur.com/NsEfl6P.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
The credential scan is complete:  <br/>
<img src="https://imgur.com/56dNqxF.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
Our virtual machine's vulnerability in depth:  <br/>
<img src="https://imgur.com/HFnMvhE.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
The problem:  <br/>
<img src="https://imgur.com/OTZL10s.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
In simpler terms:  <br/>
<img src="https://imgur.com/5VUj85Z.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
The location of the problem:  <br/>
<img src="https://imgur.com/EGu12S1.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
Solving the problem:  <br/>
<img src="https://imgur.com/ENENiWv.png" height="80%" width="80%" alt="Vulnerability Management Steps"/>
<br />
<br />
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
