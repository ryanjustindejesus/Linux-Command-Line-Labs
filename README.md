<h1>Installing software in a Linux Distribution</h1>



<h2>Description</h2>
In this lab, I learned how to install and uninstall applications in Linux using commands in the Bash shell. I worked with the Advanced Package Tool (APT) package manager to install and uninstall the Suricata and tcpdump applications.
<br />


<h2>Practical experience gained in this Lab</h2>

- <b>Installing applications</b> 
- <b>Installing Suricata with APT</b>
- <b>Uninstalling Suricata with APT</b> 
- <b>Installing tcpdump with APT</b>
- <b>Listing all installed applications</b> 

<h2>Environments Used </h2>

- <b>Qwiklabs</b> 

<h2>Lab walk-through:</h2>
 <h2>Task 1: Ensure that APT is installed </h2>
 First, I checked that the APT application is installed so that I can use it to manage applications. 
 <br /> <br />
(1) I used the command "apt" to confirm apt is installed in bash. 
<br/> <br /> <p align="center">
<img src="https://i.imgur.com/EJoj96g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> <br />

 <h2>Task 2: Install the Suricata application</h2>
In this task, I installed Suricata, a network analysis tool used for intrusion detection, and verify that Suricata installed correctly.
 <br /> <br />
(2) I used the command "sudo apt install suricata" to install suricata with apt. <br/> <br/>
Sudo: Temporarily grants elevated permissions to specific users; users must be in a sudoers file to use have access to sudo.
<br/> <br/> <p align="center">
<img src="https://imgur.com/Vpo0tjS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> <br />v

  <h2>Task 3: Uninstall the Suricata application</h2>
In this task, I installed Suricata and verify that Suricata uninstalled correctly.
 <br /> <br/>
(3) I used the command "sudo apt remove Suricata" to uninstall Suricata with apt. 
<br/> <br/> <p align="center">
<img src="https://imgur.com/keopNUf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> <br />

  <h2>Task 4: Install the tcpdump application</h2>
In this task, I installed the tcpdump application. This is a command-line tool that can be used to capture network traffic in a Linux Bash shell.
 <br /> <br />
(4) I used the command "sudo apt install tcpdump" to install tcpdump with apt.  
<br/> <br/> <p align="center">
<img src="https://imgur.com/BjIHX00.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> <br />

  <h2>Task 5: List the installed applications</h2>
In this task, I confirmed that I have installed the required applications. 
<br /> <br />
(5) I used the command "apt list --installed" to list all installed applications.  
<br /> <br /> <p align="center">
<img src="https://imgur.com/LQUVeyX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> <br />
