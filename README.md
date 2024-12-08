# Company-Network-Design
I'm happy to share my recent Cisco Packet Tracer project, Company Network Design, in which I created and set up a safe and effective corporate network. Important points to note are: OSPF Routing Protocol, VLAN &amp; Inter-VLAN, Subnetting, DHCP Server, SSH, NAT, Access Lists, Port Security 
A trading company Centre has 600 staff. A building has been identified but has no network. This means that before they can make to move out, new network service needs to be designed and implemented in the new building. 
The building is expected to have three floors with two departments in each; 
1)	First Floor (Sales and Marketing & Human Resource and Logistics) 
2)	Second Floor (Finance and Accounts, Administrator and Public Relations Department) 
3)	Third Floor(ICT, Server Room) 
Requirements: 
1)	Use Packet tracer to design and implement the network solution. 
2)	Use hieratical model providing redundancy at every layer (2 routers and two multilayer switches are expected to used to provide redundancy) 
3)	The network is also expected to connected to at least two ISP’s to provide redundancy and each router to the connected two ISP’s.
4)	Each department is required to have a wireless network for the users.
5)	Each department should be in a different VLAN and in different subnetwork.
6)	Provided a base network of 172.16.1.0 carry out subnetting to allocate he correct number of IP address to each department.
7)	The company network is connected to the static public IP address 195.136.17.0/30, 195.136.17.8/30, 192.168.17.12/30 connected to the two internet providers.
8)	Configure basic device settings such as Hostnames, console password, enable password, banner message, disable IP domain lookup. 
9)	Devices in all departments are required to communicate with each other with the respective multilayer switch configured for inter-vlan routing. 
10)	The Multilayer switches are expected to carry out both routing and switching functionalities thus will be assigned IP address. 
11)	All devices in the network are expected to obtain IP address dynamically from the dedicated DHCP servers located at the server room. 
12)	Devices in the server room are to be allocated IP address statically.
13)	Use OSPF as the routing protocol to advertise both on the routers and Multilayer Switches. 
14)	Configure SSH in all routers and layer 3 Switches for remote login. 
15)	Configure port-security for the finance and Accounts department to allow only one device to connect to a switchport, use sticky method to obtain mac-address and violation mode shutdown. 
16)	Configure PAT to use to the Respective outbound router interface IPv4 address, implement the necessary ACL rule. 
17)	Test communication, ensure everything configured is working as expected. 
