# Telecommunication Company Design & Implementation
<h2>Introduction</h2>
<p>Cairo Telco is a fast-growing telecommunication company in Egypt, which offers IT solutions and services to its clients. The company is located in the Egyption capital city, Cairo, and has occupied the fourth and fifth floors of Pharaoh's Mega Plaza. The company has its fourth and fifth floors of Pharaoh's Mega Plaza. The company has its fourth floor hosting HR and Finance(40), Product Brand and Marketing(45), and finally, Admin and Corporate departments(35). The fifth floor is designed for IT Network & Support(45), Software Engineering(36), and Cloud Engineering departments(32).
</p>
<p>
As part of ICT infrastructure, the company has subscribed to Seacom ISP for internet services and also has pruchased one 5525-X Cisco ASA Firewall, one Catalyst 3850 48-Port Switch, 3 Catalyst 2960 48-Port Switches, 2 Catalyst 2960 24-Port Switches, 1 Cisco Voice Gateway, 1 Cisco WLC, and Radius Server, the server is responsible for DNS services and for allocating IPv4 addresses to the DHCP hosts in the network. The company has an internally hosted ERP system, Email server and File server. The company has settled on using Cisco Voice Gateways to provide VoIP or telephony services in the network and Cisco WLC to provide central management for Aps. 
</p>
<p>
Cairo Telco leverages using Microsoft Azure cloud platform to facilicate service delivery thus this is one of the core business functions of the firm. The developers and cloud engineers use several MS Azure resources like VM, blob storage, networking and security among others to ensure seamless business coninuity. The proposed network should allow the team access to these resources.
</p>
<p>
Due to security requirements, it has been decided that all LAN, WLAN and VoIP users will be on a separate network segment within the same local area network. The firewall will be used to set srcurity zones and filter traffic that moves in and out of the zones based on the configured inspection policies.
</p>

 
<h2>Requirements</h2>
 <p>As a network security engineer to design the network for Cairo Telco according to the requirements set by the senior management. Consult an appropriate robust network design model to meet the design requirements. You are required to design and implement a secured, reliable, scalable and robust network system that is paramount to safeguarding the Confidentiality, Integrity and Availabiltiy of data and communication. The company has emphasized high performance, redundancy, scalability and availability. Teh company will be using the following IP address: <b>192.168.10.0/24 for LAN</b>, <b>172.16.0.0/24 for data</b>, <b>10.10.10.0/24 for voice</b>, <b>10.10.10.0/28 for DMZ</b> and <b>197.200.100.0 for public addresses</b>.<br><br>

1. <b>Design Tool</b> -  Use Cisco Packet Tracer to design and implement the network solution.
2. <b>Hierarchical Design</b> - Use a hierarchical model providing redundancy.
3. <b>ISPs</b> - THe network is also expected to connect to a Seacom ISP Router.
4. <b>WLC</b> -  Each department is required to have WAP providing both employees and guest WIFI managed by WLC.
5. <b>VoIP</b> - Each department should have IP phones.
6. <b>VLAN</b> - The The LAN, WLAN and VoIP VLANs remain at 50, 60 & 101 respectively for the entire network.
7. <b>EtherChannel</b> - Use standard LACP as a method of link aggregation.
8. <b>STP PortFast and BPDUguard</b> - configure the two protocols to enable faster prot transition from blocking to forwarding.
9. <b>Subnetting</b> - Provided the networks above, carry out subnetting to allocate the correct number of IP addresses to each department.
10. <b>Basic settings</b> - Configure basic device settigns such as hostnames, and console passwords, enable passwords and banner messages, encrypt all passwords, and disable IP domain lookup.
11. <b>Inter-VLAN Routing</b> - Devices in all the departments are required to communicate with each other with the respective multilayer switch configured for itnr-VLAN routing.
12. <b>Core Switch</b> - The Multilayer switches are expected to carry out both routing and switching functionalities and thus will be assigned IP addresses.
13. <b>DHCP Server</b> - All devices in the network (expect IP phones) are expected to obtain an IP address dynamically from the AD servers located at the server farm site.
14. <b>Cisco 2811 Router</b> - Ensure to have a router that can supprot telephony service such as Cisco Catalyst 2811 (the VoIP router should be connected to the 13-switch).
15. <b>Static Addressing</b> - Devices in the server room are to be allocated IP addresses statically.
16. <b>Telephony Service</b> - Configure VoIP on the voice gateway router and allocate dial numbers in format(1...).
17. <b>Routing Protocol</b> - OSPF as the routing protocol to advertise routes both on the routers and multilayer switches.
18. <b>Standard ACL for SSH</b> - configure a simple standard ACL on line VTY to allow only the Senior Network Security Engineer to carry out all remote administrative tasks using SSH.
19. <b>Cisco ASA Firewall</b> - Configure security levels, zones and policies to define how resources are accesses in the network.

<h2>Result</h2>
<img src="https://raw.githubusercontent.com/Jackiedee1223/image-repos/5b028134805ba2b26edaaf3bd33b0d9d0a85fecd/Network%20Design.png">

<h2>Reference</h2>
<p>Learning from GURUTECH NETWORKS </p>

