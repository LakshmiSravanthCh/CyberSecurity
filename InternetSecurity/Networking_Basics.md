The 7 layers of Networking:  
7. Application  
6. Presentation  
5. Session  
4. Transport  
3. Network  
2. Data Link  
1. Physical  

These 7 layers refer to the _Open Systems Interconnection(OSI)_ model, a conceptual framework that describes the functions of a networking or telecommunication system. 

__Layer 7 - Application:__
Its the layers most users will see. In the OSI model, this is the layer that is the layer that is the closest to the end user. Applications that work at the layer 7 are the ones that users interact with directly.

__Layer 6 - Presentation:__
The Presentation Layer represents the area that is independent of data representation at the application layer - in general, it represents the preparation or translation of application format to network format, or network formating to application format. In other words, the layer "presents" the data for the application and the network. 
- Encryption and decryption of data for the secure transport occurs at this layer.

__Layer 5 - Session:__
When 2 devices, computers or servers need to "speak" with one another, a session needs to be created, and this is done at the Session Layer. Functions at this layer involve setup, coordination (how long the system should wait for the response) and termination between the application at the end of the session.

__Layer 4 - Transport:__
The transport layer deals with the co-ordination of the data transfer between end systems and hosts. How much data to send, at what data to send, at what rate, where it goes, etc. 
- Eg: TCP which is built on top of IP. TCP works at the Layer 4 where as the IP protocol works at the Layer 3.

__Layer 3 - Network:__
At the network layer if where you will find most of the router functionality that most networking professionals care about. In its most basic sense this layer is responsible for packet forwarding, including routing through different routers. 

__Layer 2 - Data Link:__
The Data link layer provides node-to-node data transfer (between 2 directly connected nodes.), and also handles errror correction from the physiscal layer. _2 Sublayers_ exist here as well:
- Media Access Control layer
- Logical link control layer.
In the networking world, most switches operate at layer 2.

Data bits are encoded, decoded and organized in the data link layer, before they are transported as frames between 2 adjacent nodes on the same LAN or WAN. The data link layer also determine how devices recover from collisions that may occur when nodes attempt to send frames at the same time.

The role of LLC sublayer is to control data flow among applications and services, as well as provide acknowledgement and error notification mechanisms. The LLC sublayer can then talk to a number of MAC sublayers, which controls access to the physical media for transport.

Two common MAC layer types:
- Ethernet
- 802.11

__Layer 1 - Physical:__
The electrical and physical representaion of the system.


# Networking Basics:
Networks are made up of many devices: 
- computers, routers, switches, connected together by cables, wireless signals. 
- IP addresses: how devices on a network can be found.
- Network hubs, switches and cables: The hardware building blocks of any network.
- Routers and firewalls: how to organise and control the flow of traffic on a network.

## IP Addresses:
In oredr to send and direct packets through the network, computers need to be able to identify destinations and origins. This identification is an IP address. 

## Network Hubs and Switches:
Switches control only the packets intended for certain number of IP addresses to pass through switchs. The switch only know about the addresses of the computers that are switched directly into the switch. So you can only send messages to a small number of devices - how many ports the switch has. If you need to send a mesaage to a computer on another network, it will need to be sent through a router.

- __DHCP:__ Dynamic Host configuration protocol: It assigns IP address to client devices, such as desktop computers, laptops, and phones, when they are plugged into Ethernet or connected a wireless networks.
- __Hub:__ A network device that repeats the traffic it receives to all connected devices.
- __Ethernet:__ A type of networking protocol- it defines the type of cables and connections that are used to wire computers, switches, and routers together. Most often cabling is Category 5 or 6.
- __Switch:__ A network device that sends traffic it receives to a specific connected device, such as a single desktop computer or laptop.
- __Router:__ A network device that can bridge between different networks, determine what traffic can pass between them, and perform other functions on a network, such as assigning IP addresses.
- __Firewall:__ A function typically performed by routers, this filters traffic between networks and can protect them from interference or attacks. 
