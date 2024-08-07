<h1>EDR-SOAR-Project</h1>



<h2>Description of tool</h2>
Cisco Packet Analysis allow network administrators and engineers to simulate, monitor, and analyse network behaviour, aiding in the detection of issues, performance optimization, and security enforcement. By using Cisco Packet Tracer, users can create detailed network topologies, simulate various scenarios, and visualize data flow across the network. 
<br />


<h2>Project Objective</h2>

- <b>Investigate Devices in a Wiring Closet</b> 
- <b>Connect End Devices to Networking Devices</b>
- <b>Install a Backup Router</b> 
- <b>Configure a Hostname</b>


<h2>Program walk-through:</h2>



<p align="center">
Step 1: I began by navigating the city (Seward) and the Branch office, I needed to investigate the Branch Office wiring closet <br/>
<img src="https://i.imgur.com/9g4KVoi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 2: Connected PC_1 FastEthernet0 to an empty FastEthernet port on ALS2 switch<br/>
<img src="https://i.imgur.com/DqhdwfR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <br/>
<img src="https://i.imgur.com/eUO22MY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 3: I tethered RS232 port on PC_1 to the Console port on the Edge_Router. Besides a console cable, a PC can also use a USB cable to connect to a newer networking device with a mini-USB port for configuration purposes  <br/>
<img src="https://i.imgur.com/fcEVVjW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 4: I Installed Backup_Router in the Rack and turn the power on, connecting Laptop_1 to the Backup_Router with a USB cable  <br/>
<img src="https://i.imgur.com/XlzUA0K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/LThLgHo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 5: Here I configured the hostname on Backup_Router. After the hostname has been configured, the hostname appears as part of the IOS command prompt. The host name is used to identify a device when accessing its operating system for configuration.  <br/>
<img src="https://i.imgur.com/SBfvOqF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
