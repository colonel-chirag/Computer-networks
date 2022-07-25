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

