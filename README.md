# Telecommunication Company Design & Implementation
<h2>Introduction</h2>
<p>Smile University is a large university which has two campuses situated 20 miles apart. The university's students and staff are distributed in 4 faculties; these include the faculties of:<br> 
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &#x2022; Faculty of Business (FOB)<br> 
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &#x2022; Faculty of Law (FOL)<br> 
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp &#x2022; Faculty of Information, Sains and Technology (FIST)<br> 
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &#x2022; Faculty of Engineering & Technology (FET)<br> 
</p>

<h2>Requirements</h2>
 <p> Create a network topology with the main components to support the following:<br><br>
  <b>Main campus:</b> <br>
<b>Building-A</b> is the dministrative staff in the departments of management, HR and finance. The admin staff PCs are distributed in the building offices and it is expected that they will share some networking equipment (VLAN). 
  The Faculty of Business is also situated in this building. 
  <b>Building-B</b> is Faculty of Engineering and Laws. <br>
  <b>Building-C</b> is Students' labs and IT department. 
  The IT department hosts the University Web Server and other servers. 
  There is alos an email server hosted externally on the cloud.<br><br>
 <b>Sub campus:</b> <br>
<b>Faculy of Cinematic Arts(FOC)</b> is staff and student's labs are situated on separated floors.


Each department/faculty is expected to be on its own separate IP network.
The switches should be configured with appropriate VLANs and security settings.
RIPv2 will be used to provide routing for the routers in the internal network and static routing for the external server.
The devices in building A will be expected to acquire dynamic IP addresses from a router-based DHCP server.</p>

<h2>Technologies Implemented</h2>
<p>1. Expected to configure the core devices and few end devices to provide end-to-end connectivity and access to the internal servers and the external server.</p>
<p>2. Each faculty/department is expected to be on its own separate IP network. The switches should be configured with appropriate VLANs and security settings.</p>
<p>3. RIPv2 will be used to provide routing for the routers in the internal network and static routing for the external server.</p>
<p>4. The devices in building A will be expected to acquired dynamic IP address from a router-based DHCP server.</p>
<p>5. VLANs, Inter-VLAN Routing (Router on a stick), DHCP Server, Port-Security, SSH, WLAN.</p>

<h2>Result</h2>
<img src="https://raw.githubusercontent.com/Jackiedee1223/image-repos/5b028134805ba2b26edaaf3bd33b0d9d0a85fecd/Network%20Design.png">

<h2>Reference</h2>
<p>Learning from GURUTECH NETWORKS </p>

