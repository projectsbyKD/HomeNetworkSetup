<h1>Home Network Setup</h1>

<h2>Description</h2>
Project consists of a setting up home network by deploying and connecting the network devices. End devices were then configured and connectivity was verified<br />


<h2>Utilities Used</h2>

- <b>Cisco Packet Tracer</b> 
  

<h2>Environments Used </h2>

- <b>Windows 11</b> 

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/IrtxO1F.png"/>
<br />
<br />
Add network devices to workspace:  <br/>
<img src="https://i.imgur.com/kcZYi9L.png"/>
<br />
<br />
Add physical cabling between devices on network: The PC will need a copper straight through cable to connect to the wireless router. It will connect to the FastEthernet0 interface of the PC and Ethernet1 interface of the wireless router. The wireless router will need a copper straight through cable to connect to the cable modem. It will attach to the internet interface of the wireless router and the Port 1 interface of the cable modem. The cable modem wil need a coaxial cable to connect to the internet cloud. It will attach to the Port0 interface of the cable modem and the coaxial 7 interface of the internet cloud.    <br/>
<img src="https://i.imgur.com/POmmGDR.png"/>
<br />
<br />
Configure the PC: Verify that DHCP is enabled and the computer recieved an IP address. Use comand propmts to verify IP was given and computer can connect (ipconfig /all) (ping ciso.srv).  <br/>
<img src="https://i.imgur.com/W0ajS4X.png"/>
<br />
<br />
Configure the laptop: The laptop had a Ethernet copper module that had to be replaced with a WPC300N. After replacing, power laptop on and connect to HomeNetwork. Then use the web browser to verify connectivity.   <br/>
<img src="https://i.imgur.com/Nxy8ps8.png"/>
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
