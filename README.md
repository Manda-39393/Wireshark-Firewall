# Wireshark-Firewall
<p align="center">
<img src="" alt="https://i.imgur.com/FfOEYxy.png" />
</p>

<h1>Wireshark  - Prerequisites and Installation</h1>
Brief tutorial on how to install and observe firewall.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Ubuntu 

<h2>List of Prerequisites</h2>

- Created Resouce Group
- Windows/Ubuntu Virtual Machines

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/WYsfRU5.png" height="80%" width="80%"/>
</p>
<p>
1. Use remote Desktop to connect to Windows 10 Virtual Machine (take a moment to check the topology, via Azure)
</p>
<br />

<p>
<img src="https://i.imgur.com/yGc1e9W.png" height="80%" width="80%"/>
</p>
<p>
2. Login using created username and password.
3. Download Wireshark via, Wireshark.com.

</p>
<br />

<p>
<img src="https://i.imgur.com/vRJVQ5h.png" width="80%"/>
</p>
<p>
4. Download and install Wireshark.
</p>
<br />

<p>
<img src="https://i.imgur.com/1v6bEPj.png" height="80%" width="80%"/>
</p>
<p>
6. Observe ICMP Traffic.

<p>
<img src="https://i.imgur.com/Ag3CujO.png"80%" width="80%"/>
</p>
<p>
7. Ping private address of Ubuntu VM and ping address in Windows
<p>
  
<img src=https://i.imgur.com/rWaLDtN.png"" height="80%" width="80%"/>
</p>
<p>
8. In Wireshark put IMCP in the search area, observe traffic, and prepare to block chosen traffic.

<p>
<img src="https://imgur.com/a/pXNbiPt" height="80%" width="80%"/>
</p>
<p>
9. Observe traffic. ***this is supposed to be the DHCP not DNS***
</p>
<br />

<p>
<img src="https://i.imgur.com/bBy3X7X.png" height="80%" width="80%"/>
</p>
<p>
Assign permissions via properties, click on security and click advanced, disable inheritance.
</p>
<br />

<p>
<img src="https://i.imgur.com/WZ2Crtf.png" height="80%" width="80%"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/T5pmnEE.png" height="80%" width="80%"/>
</p>
<p>
Click and remove all ineherited permissions from the object, click set principal, enter "everyone" in display box, and click check.
</p>
<br />

<p>
<img src="https://i.imgur.com/W6NC83u.png" height="80%" width="80%"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/zcWMK05.png" height="80%" width="80%"/>
</p>
<p>
Open Heidi SQL, click on unnamed and click create a new database, create database and rename to osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/6W2EnRG.png" height="80%" width="80%"/>
</p>
<p>
Continue to enter in information in osTicket; successfully installed osTicket.
</p>
<br />

<p>
