<h1>Installing software in a Linux Distribution</h1>



<h2>Description</h2>
In this lab, I learned how to install and uninstall applications in Linux using commands in the Bash shell. I worked with the Advanced Package Tool (APT) package manager to install and uninstall the Suricata and tcpdump applications.
<br />


<h2>Completed Tasks in this Lab</h2>

- <b>Confirming APT is installed in Bash</b> 
- <b>Installing Suricata with APT</b>
- <b>Uninstalling Suricata with APT</b> 
- <b>Installing tcpdump with APT</b>
- <b>Listing all installed applications</b> 

<h2>Environments Used </h2>

- <b>Qwiklabs</b> 

<h2>Lab walk-through:</h2>
 <h2>Task 1: Ensure that APT is installed </h2>
<p align="center">
(1) I used the command "apt" to confirm apt is installed in bash. <br/>
<img src="https://i.imgur.com/EJoj96g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <h2>Task 2: Install the Suricata application</h2>
<p align="center">
(2) I used the command "sudo apt install suricata" to install suricata with apt.  <br/>
<img src="https://imgur.com/Vpo0tjS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  <h2>Task 3: Uninstall the Suricata application</h2>
<p align="center">
(3) I used the command "sudo apt remove suricata" to uninstall suricata with apt. <br/>
<img src="https://imgur.com/keopNUf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  <h2>Task 4: Install the tcpdump application</h2>
<p align="center">
(4) I used the command "sudo apt install tcpdump" to install tcpdump with apt.  <br/>
<img src="https://imgur.com/BjIHX00.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  <h2>Task 5: List the installed applications</h2>
<p align="center">
(5) I used the command "apt list --installed" to list all installed applications.  <br/>
<img src="https://imgur.com/LQUVeyX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
