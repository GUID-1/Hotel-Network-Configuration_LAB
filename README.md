# Hotel-Network-Configuration_LAB
Configure a Hotel Network topology using elements of networking such as: DHCP, Routing protocols, VLANS, End devices, IP addressing, APs, &amp; Switchports

<h1>Hotel Network Packet Tracer Lab</h1>

 ### [YouTube Demonstration](https://youtu.be/2eN5QdSPeBk)

<h2>Description</h2>
Project consists of a configuring a hotel network topology that incorporates the configuration of DHCP, SSH, Routing protocols, End devices, VLANS, 802.1Q encapsulation, APs, & static IP addressing & switchports 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco CLI</b>

<h2>Cisco CLI Commands Used</h2>

- <b>Enable (en)</b>
- <b>Configure Terminal (conf t)</b>
- <b>Do Show Vlan (do sh vlan)</b>
- <b>Do Show Interfaces Status (do sh interfaces status)</b>
- <b>Interface Range (int range)</b>
- <b>Switchport Mode Access (sw mod acc)</b>
- <b>Switchport Access vlan (sw acc vlan)b>
- <b>Do Write (do wr)</b>
- <b>Do Show Run (do sh run)</b>
- <b>Switchport Mode Trunk (sw mod trunk)</b>
- <b>Do Show Controllers Serial (do sh controll se)</b>
- <b>Clock Rate(clock ra)</b>
- <b>Service DHCP (service dhc)</b>
- <b>IP DHCP Pool (ip dhcp pool)</b>
- <b>Network (netwo)</b>
- <b>Default-Router (defaul)</b>
- <b>DNS-Server (dns)</b>
- <b>Domain-Name (domai)</b>

<h2>Environments Used </h2>

- <b>Packet Tracer 9.0</b> 

<h2>Configuration walk-through:</h2>

<p align="center">
VLAN configuration F1-SW: <br/>
<img src="https://www.image2url.com/r2/default/images/1788504285250-b880c2f2-991e-4298-bdbe-046e53688638.png" alt="VLAN Configuration Steps" />
<br />
<br />
Switchport Access Config F1-SW:  <br/>
<img src="https://www.image2url.com/r2/default/images/1788505234571-e8015674-d758-4f00-b413-792fe24ee290.png" alt="Switchport Access Config Steps" />
<br />
<br />
Switchport Access Config (F1-SW): <br/>
<img src="https://www.image2url.com/r2/default/images/1788505508552-c4bab3c9-9dc0-405b-bf2d-af95d6de676a.png" alt="Switchport Access Config Steps Con't" />
<br />
<br />
VLAN & Switchport Configuration (F2-SW):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788506182948-7cda4963-8e2b-42c8-b2b5-c69a612a4847.png" alt="VLAN & Switchport Configuration" />
<br />
<br />
VLAN & Switchport Configuration (F3-SW):   <br/>
<img src="https://www.image2url.com/r2/default/images/1788506585817-a02da533-cae0-4880-85a7-d21f04324416.png" alt="VLAN & Switchport Configuration" />
<br />
<br />
VLAN & Switchport Configuration (F3-SW) Con't:  <br/>
<img src="https://www.image2url.com/r2/default/images/1788506708233-b6918cd6-4466-4ad0-9c83-41b14c5355dc.png" alt="VLAN & Switchport Configuration Con't" />
<br />
<br />
Switchport Mode Trunk Configuration (F1-SW):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788507461589-8b76ceab-a7dc-4f07-89d9-6ee97c1e547b.png" alt="Switchport Mode Trunk Config" />
<br />
<br />
Switchport Mode Trunk Configuration (F2-SW):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788507684843-f84e48d9-9ed9-4e49-a214-f7a9b5dd9230.png" alt="Switchport Mode Trunk Config" />
<br />
<br />
Switchport Mode Trunk Configuration (F3-SW):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788507863661-20c318c1-6c35-4ddf-92be-64da2d79f962.png" alt="Switchport Mode Trunk Config" />
<br />
<br />
Router Interface Configuration (F1-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788508568708-29d0b6af-e0ff-47a8-b966-5f64035be014.png" alt="Router Config" />
- Use the "no shut" command on each interface 
<br />
<br />
Router Interface Configuration (F2-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788509425307-f57b6192-b2f6-45fb-9da9-9929ff1c3293.png" alt="Router Config" />
<br />
<br />
Router Interface Configuration (F3-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788509232524-a345dac9-2453-4443-ba22-4c538fcb89eb.png" alt="Router Config" />
<br />
<br />
Router Clock Rate Configuration (F1-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788509938431-226ba843-6248-49ae-9e05-f62244900e2e.png" alt="Clock Rate Config" />
- Set the clock rate to 64000 for each DCE interface  
<br />
<br />
Router Clock Rate Configuration (F2-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788510169621-f8dacb1a-d7b9-4ec7-926a-af3b0b15d688.png" alt="Clock Rate Config" />
<br />
<br />
Router DHCP Configuration (F1-Router):  <br/>
<img src="https://www.image2url.com/r2/default/images/1788510448507-9315a0ed-e977-4549-8f15-327e9a816977.png" alt="DHCP Config" />
<img src="https://www.image2url.com/r2/default/images/1788510638622-341b58a7-b259-4203-b095-e224c25f6c3a.png" alt="DHCP Config" />
<img src="https://www.image2url.com/r2/default/images/1788510781563-34f082b1-452b-4dbf-8428-931d0e020c1b.png" alt="DHCP Config" />
<br />
<br />
  SOP: Configure a Hotel Network with VLANs, DHCP, Wireless Access, Switchport Access, IP Addressing

### Objective


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
