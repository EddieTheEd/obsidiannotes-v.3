---
layout: default
title: "Comp Sci 7"
---

Conf. between **router and device**, and **device and device** is needed.

Concept of networking is that 2 or more entities(devices) that are able to connect to each other

### Network Classification
- Geographical Area: PANs, LANs, WANs, etc.
- Design: Peer to peer, **client** to server
	- Client to server is the **most important**
	- Peer to peer works with just simple connections (computer to computer)
- Layout: Topology (Bus, Start, Ring, etc.)
- Protocols: TCP/IP, HTTP, HTTPS, etc.
### Topologies
- Ring
	- Each device is connected to each other in circular format.
- Mesh
	- Different **types of connections**: they *cross over*. 
- Star
	- Very common
- Fully Connected
	- Considered a hybrid topology
- Line
	- Adv. connection between devices very quick
	- DisAdv. if one connection fails, the whole network breaks.
- Tree
- Bus

All these topologies have advantages and disadvantages.

**Most common:** combination of star and tree.

![](000_Files/Pasted%20image%2020221104091837.png)

### Protocols
Many types of models, for different ways of transport
- TCP/IP Model:
	- Application
		- Person A send email to B. The application layer. The data to be sent is found in the application layer
	- Transport 
		- How is the data transferred?
	- Internet
		- Address of device sending + address of device receiving
		- DIfference between IPv4 and IPv6:
			- v4: 32 bit address
				- Number of ip addresses running out
				- uses 1010
				- Older
			- v6: 128 bit address
				- Uses hexadecimal numbers?
				- uses 1010 + hex
				- Newer
			**Both used at the same time**
	- Link
		- Type of transmission media in which this data is sent.
		- Maximum distance of bluetooth: **5m**
		- Ethernet cable is the most popular link protocol. There are two types:
			- UTPC - Unshielded Twisted Pair Cable
				- Set of 4 pairs of twisted cables.
				- In the middle, there is usually a separation. This results in 2 more types of cables:
					- CAT5
						- Doesn't have the separator in the middle.
					- CAT6
						- Has separator. This is used to defend against **interference**
			- STPC - Shielded Twisted Pair Cable
			- **Ethernet cables are generally 100m viable length!!!**
		- Another Link protocol is Fibre-optic cables, different types *for different needs*:
			- Single Mode
				- One packet of data at a time
				- **Sends 1 packet of data at a time.**
				- **Longer range and faster**
			- Multi Mode
				- Multiple packets of data at a time
				- Can send **more data in shorter period of time**
				- **Shorter range and slower**
			-  e.g. in building to building, distance not that fast, so can use multi mode, in school to use, distance long, so use single mode
		- Another one is **coaxial cables**
			- Thick diameter of copper cables with multiple layers of protection
			- This is very expensive, so only used for specific cases!
	- **The reverse way is how someone receives the data!!!**
		- This reverse way are called the **protocols**. 
		- **Wireless Examples:**
			- Broadcast Satellite
			- Microwave
				- Main Disadvantage, there has to be a direct, clear line between the 2 devices. If there is an object obstructing the transmission, the data is damaged(?)
			- Cellular
				- Tower provides access to multiple mobile devices. This tower connected to another tower, which provides access to other mobile devices, etc.
				- This is called **cellular**, because one tower connected to multiple devices is **one cell**.
			- WiFi
				- Device that provides access in a small area of connectivity.
- OSI Model
![](000_Files/Pasted%20image%2020221104092753.png)

### Hardware
- Typically, networking hardware includes:
	- Routers
	- Bridges
	- Switches
	- Hubs
	- Repeaters
	- Gateways

Devices:
- Computer
- Printer
- Wireless tablet
- WAP
- 3 things in a device (gateway):
	- Modem (see below)
	- Firewall 
		- Software that filters packets of data that come into a **local network**
	- Router
### Bridge
- "like a switch" (this is me speaking now) "for networks"
- ~~Receive messages distributed through a network and sends to other networks.~~
- Connects **network segments** within a domain together.

### Switches
- Switches have 5-48 ports. 24 ports is common.
- Switches connect many devices to each other in a network.
- Routers send and receive data from another network to the switch, switch sends and receives this data to other devices. 

### Modem
- Converts analogue data to digital data, and vice versa.
- Comes from "**Mo**dulate, **Dem**odulate".
	- I.e. convert one type of data to another, vice versa

### Router
- Send packets of data to other networks

### Packets of data:
- Packets are sent in **bytes**!
- Bytes are 8 bits!
	- Bits are binary numbers.
- e.g. 1 packet could be 01010101
- All this numbers are just electrical inputs sent through copper cables. It comes out as ones and zeroes, but we aren't actually transmitting ones and zeroes.
- 1 - ON
- 0 - OFF
- During an electrical storm, and using a satellite, there *is a chance* that the data is received differently.
- e.g. from 01010101 to 01010010
- This is called a bitflip, and **computers have evolved to fight against bitflips**. For example, if a computer cannot recognise a packet, it will return the packet.
- Even parity: N(ones) is the same
	- ~~Odd parity: N(ones) is not the same~~
- Lets say packets were even parity, then knowing what the parity is, a computer can check the packet and see whether its still even parity.
	- This has flaws. Let's say that a packet has 3 ones. Bitflips can occur that maintain 3 ones. This means the packet is not returned, if using even parity.

### Network Diagram
![](000_Files/Pasted%20image%2020221104101741.png)

> [!NOTE] Important!
> Use Cisco System for default diagrams.

![](000_Files/Pasted%20image%2020221106191623.png)

> [!NOTE] VERY IMPORTANT!
> Learn Cisco Diagrams!!!!

certified mr wilson moment
