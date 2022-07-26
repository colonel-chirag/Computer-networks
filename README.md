# Computer-networks

What is the network?

According to Merriam Webster, Network is usually an informally interconnected group or association of different entities like a person, computers, radio stations, etc.

For example, Dominos has a network of 1232 branches across India. As the name suggests the computer network is a system of peripherals or computers interconnected with each other and has a standard communication channel established between them to exchange different types of information and data.

Why is the computer network so important?

Have you ever heard of the Internet or NET? I guess you have, as you are already reading this article on Interviewbit surfing through the internet. But, have you ever thought about the internet? The Internet is a network of a network connecting all different network-enabled devices which enable data and information sharing between them and that makes computer networks a core part of our life and technical interviews.

Below is the list of all commonly asked networking questions in technical interviews from basic to advanced level.
Basic Networking Interview Questions
1. How are Network types classified?
Network types can be classified and divided based on the area of distribution of the network. The below diagram would help to understand the same:


Network Types

![image](https://user-images.githubusercontent.com/59536110/180772837-f1b691d1-0a5c-47aa-9f8b-01f681da4d9e.png)

3. Explain LAN (Local Area Network)
LANs are widely used to connect computers/laptops and consumer electronics which enables them to share resources (e.g., printers, fax machines) and exchange information. When LANs are used by companies or organizations, they are called enterprise networks. There are two different types of LAN networks i.e. wireless LAN (no wires involved achieved using Wi-Fi) and wired LAN (achieved using LAN cable). Wireless LANs are very popular these days for places where installing wire is difficult. The below diagrams explain both wireless and wired LAN.
![image](https://user-images.githubusercontent.com/59536110/180772918-b5566d48-5a7a-44be-b9a2-eec6de838fcb.png)
LAN (Local Area Network)

4. Tell me something about VPN (Virtual Private Network)
VPN or the Virtual Private Network is a private WAN (Wide Area Network) built on the internet. It allows the creation of a secured tunnel (protected network) between different networks using the internet (public network). By using the VPN, a client can connect to the organization’s network remotely. The below diagram shows an organizational WAN network over Australia created using VPN:


VPN (Virtual Private Network)
5. What are the advantages of using a VPN?
Below are few advantages of using VPN:

VPN is used to connect offices in different geographical locations remotely and is cheaper when compared to WAN connections.
VPN is used for secure transactions and confidential data transfer between multiple offices located in different geographical locations.
VPN keeps an organization’s information secured against any potential threats or intrusions by using virtualization.
VPN encrypts the internet traffic and disguises the online identity.
6. What are the different types of VPN?
Few types of VPN are:
![image](https://user-images.githubusercontent.com/59536110/180773094-a0fc7bed-5211-44e8-99a7-59cf026cf7c0.png)

Access VPN: Access VPN is used to provide connectivity to remote mobile users and telecommuters. It serves as an alternative to dial-up connections or ISDN (Integrated Services Digital Network) connections. It is a low-cost solution and provides a wide range of connectivity.
Site-to-Site VPN: A Site-to-Site or Router-to-Router VPN is commonly used in large companies having branches in different locations to connect the network of one office to another in different locations. There are 2 sub-categories as mentioned below:
Intranet VPN: Intranet VPN is useful for connecting remote offices in different geographical locations using shared infrastructure (internet connectivity and servers) with the same accessibility policies as a private WAN (wide area network).
Extranet VPN: Extranet VPN uses shared infrastructure over an intranet, suppliers, customers, partners, and other entities and connects them using dedicated connections.
![image](https://user-images.githubusercontent.com/59536110/180773128-a83f9b33-9e66-47a3-9dbf-9a18672d5f1d.png)

7. What are nodes and links?
Node: Any communicating device in a network is called a Node. Node is the point of intersection in a network. It can send/receive data and information within a network. Examples of the node can be computers, laptops, printers, servers, modems, etc.

Link: A link or edge refers to the connectivity between two nodes in the network. It includes the type of connectivity (wired or wireless) between the nodes and protocols used for one node to be able to communicate with the other.


Nodes and Links
8. What is the network topology?
Network topology is a physical layout of the network, connecting the different nodes using the links. It depicts the connectivity between the computers, devices, cables, etc.

9. Define different types of network topology
The different types of network topology are given below:

Bus Topology:
![image](https://user-images.githubusercontent.com/59536110/180773284-52c98b75-3fde-4312-a703-a2320edd1694.png)

Bus Topology
All the nodes are connected using the central link known as the bus.
It is useful to connect a smaller number of devices.
If the main cable gets damaged, it will damage the whole network.
Star Topology:
![image](https://user-images.githubusercontent.com/59536110/180773330-c5ca01ba-7741-4355-8eb9-7d86bebb1f5f.png)


Star Topology
All the nodes are connected to one single node known as the central node.
It is more robust.
If the central node fails the complete network is damaged.
Easy to troubleshoot.
Mainly used in home and office networks.
Ring Topology:

![image](https://user-images.githubusercontent.com/59536110/180773406-40abf74a-c602-4e64-a445-0b635fc1e6d3.png)

Ring Topology
Each node is connected to exactly two nodes forming a ring structure
If one of the nodes are damaged, it will damage the whole network
It is used very rarely as it is expensive and hard to install and manage
Mesh Topology:
![image](https://user-images.githubusercontent.com/59536110/180773439-827884f5-8e5f-488a-a706-1f358fec7546.png)


Mesh Topology
Each node is connected to one or many nodes.
It is robust as failure in one link only disconnects that node.
It is rarely used and installation and management are difficult.
Tree Topology:
![image](https://user-images.githubusercontent.com/59536110/180773478-4af881c0-e03a-47d1-a7b3-dcf4c9b81d78.png)


Tree Topology
A combination of star and bus topology also know as an extended bus topology.
All the smaller star networks are connected to a single bus.
If the main bus fails, the whole network is damaged.
Hybrid:

It is a combination of different topologies to form a new topology.
It helps to ignore the drawback of a particular topology and helps to pick the strengths from other.

![image](https://user-images.githubusercontent.com/59536110/180773557-7f7c2e1d-4cbc-4a3a-b832-21b091b565ba.png)

Intermediate Interview Questions
12. Describe the OSI Reference Model
Open System Interconnections (OSI) is a network architecture model based on the ISO standards. It is called the OSI model as it deals with connecting the systems that are open for communication with other systems.

The OSI model has seven layers. The principles used to arrive at the seven layers can be summarized  briefly as below:

Create a new layer if a different abstraction is needed.
Each layer should have a well-defined function.
The function of each layer is chosen based on internationally standardized protocols.
13. Define the 7 different layers of the OSI Reference Model
Here the 7 layers of the OSI reference model:
![image](https://user-images.githubusercontent.com/59536110/180773617-4faaa2ba-c7c3-4529-a0ce-1bb0430a424d.png)

![image](https://user-images.githubusercontent.com/59536110/180773733-6eeb437d-3cf1-48b6-971b-ca774f281a3a.png)
14. Describe the TCP/IP Reference Model
It is a compressed version of the OSI model with only 4 layers. It was developed by the US Department of Defence (DoD) in the 1980s. The name of this model is based on 2 standard protocols used i.e. TCP (Transmission Control Protocol) and IP (Internet Protocol).

15. Define the 4 different layers of the TCP/IP Reference Model

![image](https://user-images.githubusercontent.com/59536110/180773808-2735e0d9-9e7c-4434-8570-af6751b6bbb8.png)

![image](https://user-images.githubusercontent.com/59536110/180773853-d9a7ccc4-44ea-4332-8cb9-9b803f3cc5ac.png)

16. Differentiate OSI Reference Model with TCP/IP Reference Model
![image](https://user-images.githubusercontent.com/59536110/180773915-b25a4ec7-7c1a-4828-b356-a1929ec0956f.png)
![image](https://user-images.githubusercontent.com/59536110/181082295-1792f125-c3c0-400d-b396-cf24ab4b11b8.png)

17. What are the HTTP and the HTTPS protocol?
HTTP is the HyperText Transfer Protocol which defines the set of rules and standards on how the information can be transmitted on the World Wide Web (WWW).  It helps the web browsers and web servers for communication. It is a ‘stateless protocol’ where each command is independent with respect to the previous command. HTTP is an application layer protocol built upon the TCP. It uses port 80 by default.

HTTPS is the HyperText Transfer Protocol Secure or Secure HTTP. It is an advanced and secured version of HTTP. On top of HTTP, SSL/TLS protocol is used to provide security. It enables secure transactions by encrypting the communication and also helps identify network servers securely. It uses port 443 by default.

18. What is the SMTP protocol?
SMTP is the Simple Mail Transfer Protocol. SMTP sets the rule for communication between servers. This set of rules helps the software to transmit emails over the internet. It supports both End-to-End and Store-and-Forward methods. It is in always-listening mode on port 25.
![image](https://user-images.githubusercontent.com/59536110/181082374-de4bb769-2537-4306-b1bb-85f0fd745cbf.png)

19. What is the DNS?
DNS is the Domain Name System. It is considered as the devices/services directory of the Internet. It is a decentralized and hierarchical naming system for devices/services connected to the Internet. It translates the domain names to their corresponding IPs. For e.g. interviewbit.com to 172.217.166.36. It uses port 53 by default.

20. What is the use of a router and how is it different from a gateway?
The router is a networking device used for connecting two or more network segments. It directs the traffic in the network. It transfers information and data like web pages, emails, images, videos, etc. from source to destination in the form of packets. It operates at the network layer. The gateways are also used to route and regulate the network traffic but, they can also send data between two dissimilar networks while a router can only send data to similar networks.

Advanced Interview Questions
21. What is the TCP protocol?
TCP or TCP/IP is the Transmission Control Protocol/Internet Protocol. It is a set of rules that decides how a computer connects to the Internet and how to transmit the data over the network. It creates a virtual network when more than one computer is connected to the network and uses the three ways handshake model to establish the connection which makes it more reliable.

22. What is the UDP protocol?
UDP is the User Datagram Protocol and is based on Datagrams. Mainly, it is used for multicasting and broadcasting. Its functionality is almost the same as TCP/IP Protocol except for the three ways of handshaking and error checking. It uses a simple transmission without any hand-shaking which makes it less reliable.

23. Compare between TCP and UDP
![image](https://user-images.githubusercontent.com/59536110/181082471-87ec2a98-d177-4d48-96e7-b707fadd7a24.png)

24. What is the ICMP protocol?
ICMP is the Internet Control Message Protocol. It is a network layer protocol used for error handling. It is mainly used by network devices like routers for diagnosing the network connection issues and crucial for error reporting and testing if the data is reaching the preferred destination in time. It uses port 7 by default.

25. What do you mean by the DHCP Protocol?
DHCP is the Dynamic Host Configuration Protocol.

It is an application layer protocol used to auto-configure devices on IP networks enabling them to use the TCP and UDP-based protocols. The DHCP servers auto-assign the IPs and other network configurations to the devices individually which enables them to communicate over the IP network. It helps to get the subnet mask, IP address and helps to resolve the DNS. It uses port 67 by default.

26. What is the ARP protocol?
ARP is Address Resolution Protocol. It is a network-level protocol used to convert the logical address i.e. IP address to the device's physical address i.e. MAC address. It can also be used to get the MAC address of devices when they are trying to communicate over the local network.

![image](https://user-images.githubusercontent.com/59536110/181082526-559a6fed-fd5b-4528-b84b-6c7487d5823b.png)

27. What is the FTP protocol?
FTP is a File Transfer Protocol. It is an application layer protocol used to transfer files and data reliably and efficiently between hosts. It can also be used to download files from remote servers to your computer. It uses port 27 by default.

28. What is the MAC address and how is it related to NIC?
MAC address is the Media Access Control address. It is a 48-bit or 64-bit unique identifier of devices in the network. It is also called the physical address embedded with Network Interface Card (NIC) used at the Data Link Layer. NIC is a hardware component in the networking device using which a device can connect to the network.

29. Differentiate the MAC address with the IP address
The difference between MAC address and IP address are as follows:
![image](https://user-images.githubusercontent.com/59536110/181082594-ac83185a-c184-489d-beef-889d148f9841.png)

30. What is a subnet?
A subnet is a network inside a network achieved by the process called subnetting which helps divide a network into subnets. It is used for getting a higher routing efficiency and enhances the security of the network. It reduces the time to extract the host address from the routing table.
![image](https://user-images.githubusercontent.com/59536110/181082668-247ccdf1-a01c-4293-a965-ba7810518dda.png)

![image](https://user-images.githubusercontent.com/59536110/181082719-3b482ed1-0ae2-41a6-b982-560c0e5cef9f.png)

33. What is the firewall?
The firewall is a network security system that is used to monitor the incoming and outgoing traffic and blocks the same based on the firewall security policies. It acts as a wall between the internet (public network) and the networking devices (a private network). It is either a hardware device, software program, or a combination of both. It adds a layer of security to the network.
