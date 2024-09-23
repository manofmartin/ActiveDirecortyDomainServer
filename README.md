<h1>Making Active Direcorty Domain Server</h1>

<h2>Description</h2>
Creating the Active Directory domain server, assigning a static IP and configuring the features and roles.

<h2>List of Tools</h2>
- <b>Windows 2022 server</b><br />
- <b>KVM for virtualization of server</b>

<h2>Let's Begin!</h2>

<p align="center">
Login as Administrator in VM: <br/>
<img src="https://i.imgur.com/bdkkavK.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
Change the server name, configure a static IP address, and loopback for DNS server: <br/>
<img src="https://i.imgur.com/fqefDov.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/dYzgeDn.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/iDrOUv3.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/ZSpKjnT.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/uhfpKEi.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/uoRGMZI.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/gT5R4y3.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/6pK4Uj5.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/jt4IHp5.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
Reboot machine to allow for changes to be finalized: <br />
<img src="https://i.imgur.com/w1WRRzl.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
After the reboot verify changes were successful and begin assigning Active Driectory role to the machine: <br />
<img src="https://i.imgur.com/xyUS0Gk.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/AqEDQYU.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/9WFLplL.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
We are choosing Role-Based and following the prompts in this demonstration: <br />
<img src="https://i.imgur.com/PqwYoG1.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/tm1BrOv.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/5R7l9Ri.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/eHndk52.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/hoYOTUa.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/Xutz5ox.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
Beginning the instllation for the Active Directory server role: <br />
<img src="https://i.imgur.com/IeDEnRf.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/ysZd1d6.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/66V13NZ.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
Selecting "Add a new forest" to begin our first Active Directory for the Demonstration: <br />
<img src="https://i.imgur.com/UCedKCu.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
Creating a password for Domain: <br />
<img src="https://i.imgur.com/Etihfcx.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
Proceeding with the install (remaining choices are assigned automatically): <br />
<img src="https://i.imgur.com/iqqjiNH.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/nLzLoVR.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/0hRQfgp.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/sWgNBXI.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/ZOApBVk.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/odyBxx6.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/d5GqMhe.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
System prompts for a reboot to finalized changes made: <br />
<img src="https://i.imgur.com/jhMxsoC.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
After logging back in we need to verify the Active directory is present and it is it's own DNS server: <br />
<img src="https://i.imgur.com/XbhXRKg.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/91BgBSO.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/Cv5uFOG.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
We now have a functioning Active Directory server up and running! <br />
<img src="https://i.imgur.com/YXuQ7fP.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
