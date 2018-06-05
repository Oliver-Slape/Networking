# Networking
---
## Network types and Standards
---
### Peer-based
---
Peer-based is a network that connects to each other locally without a centralized administrating system. 
The main benefit of Peer-based networks is their simplicity. They don't require much hardware or any at all as they don’t need a mediator of control or authority, they just connect to each other. Because of this the resource implications are very low. They don’t require much setup compared to other networks such as servers. A constraint of Peer-based would be their scalability. They are generally not very applicable for large networks. Additionally, they have a lack of security as there is no controlling factor.

### Client-Server
---
Client-Server networks all connect to one point in LAN. They are centralized. There will be a centralized administrating system that controls all of the users in the networks and things like authentication and group policies.
The main benefit of Client-Server networks is their management. The administrating system has control over all systems in the network. Allowing for easy changes to things like passwords and access to files and data. Furthermore, it has good scalability as if the server has increased use and is being overloaded another server can be spun-up or setup to handle the increase in users. A constraint would be the costs included with Client-Server networks. The hardware has to be bought to manage the network and specific specialists are required to setup and maintain the network. Furthermore, it is not as robust. If the server goes down the whole network goes down. 

### Cloud
---
Cloud based networks are services clients will hire. They will be managed and setup by the provider but the client just pays for the server space they use and the access to it. The network is essentially Client-Server but the server aspect is run and managed by an outside party thus making it decentralized. Additionally, the majority of cloud based services will be virtualized. This is because virtualizing their servers allows them to use all of the server and not waste any unused hardware allowing them to provide the service at cheaper rates.
The benefits are that the cost is greatly reduced as you don’t need the hardware for a server or the staff to manage it. You can access the network practically anywhere and from any device. All of the security aspects are managed by the provider as well. The scalability is innovating. If a client needs more capacity or resource they can click a button and a new server space is Spun-up and available to access. Cloud networks also allow for collaboration as they provide services for clients to access and edit work at the same time in real-time. A constraint would be the lack of control of data. If a payment is missed for the services, the provider can stop access to all of the client’s data until payment is made or even remove all of their data if they miss a deadline. Furthermore, if the provider’s services fail or the internet connect required to access it fails there is no local collection of the data so it becomes inaccessible. 

## Standards and Protocols
---

### IEEE 802.3
The standard used for Ethernet protocol is IEEE 802.3. It controls the physical cables used and the way LAN and WAN networks are set up. This is maintained by the Institute of Electrical and Electronics Engineers (IEEE). The IEEE 802.3 was the first standard set for Ethernet cables. However, it has been maintained and updated with working versions such as IEEE 802.7. The standard speed for these connections must be at 10Mbps. 

### IEEE 802.7 
The subsection .7 of the IEEE 802 is related to broadband cable mediums, standards, design and parameters generally used within broadband LANs. 

### IEEE 802.8
The subsection .8 refers to standards for fibre connections used in token passing networks. This is very similar to the broadband section and covers similar topics such as connections, design and parameters. It has its own subsection because it is a different connection type and thus needs different standards. 

### IEEE 802.11 
The subsection .11 refers to standards for wireless connections. The most used example is Wi-Fi and the standard sets out guidelines for design, parameters, types of frequencies, access points and other types of network devices. 

### TCP/IP
The Transmission Control Protocol/Internet Protocol is a conceptual model that defines how communication protocols are used to connect to the internet via devices or even on private networks. The TCP/IP model is made up of four layers;

Application: This is responsible for network service control internally. This uses protocols like DNS, HTTP, and SMTP ETC

Transport: This layer maintains the protocols for end-to-end communication. This layer has many aspects, some being the TCP, UDP, Flow control, Multiplexing etc.

Internet/Network: This layer is responsible for routing the data packets to the correct network devices whether that be from inside or outside the network. This layer or packs and unpacks the data packets. The data packets contain a source, destination and address that is used to route it across networks.

Network Access: This layer manages the type of connection being used on a network and what protocols are used. It defines how data can be received and delivered over the network. 

### OSI model

Application: This layer gives access and authentication for services to send and receive data using certain protocols. Some of these are SMTP, HTTP, and DNS ETC

Presentation: This layer is responsible for coding and decoding the data packets so that the data can be accessed. Whether it be that they are encrypted or compressed. 

Session: This layer maintains the connection between applications and monitors them. It does this using protocols. The main two being TCP and UDP. 

Network: This layer is sort of like a post office. It receives or sends data packets and makes sure they have correct addresses and are sent to the correct destination. It uses IPv4, Ipv6, and IPX protocols to establish this.

Data link: This layer handles the encoding of data for transmission and decoding using encapsulation and un-encapsulation methods. This is mainly done on the physical link of the network.

Physical: This layer controls the way physical connections are managed, accessed and routed. Whether that be through cables or over network cards. 

### Routed Protocols
Routed Protocols control how data is managed across networks through an addressing system. 
?
?
?
