---
layout: default
title: "Comp Sci Networking Revision"
---

1. What is the role of the following hardware devices in a communications network?
-   Router
	- **Send and receives packets of data to and from other networks, relays to switch**
    
-   Switch
	- **Switches connect many devices to each other in a network.**
	- **Routers send and receive data from another network to the switch, switch sends and receives this data to other devices.** 
		- ***Vs. Hub: Switch is Data link on OSI model, Hub is physical***
    
-   Firewall
	- **Software that filters packets of data that come into a local network**
    
-   Modem
	- **Converts analogue data to digital data, and vice versa.**
	- Comes from "**Mo**dulate, **Dem**odulate".
		- **I.e. convert one type of data to another, vice versa**
    
-   Network Interface Card (NIC)
    - Hardware built into a device (computer) that allows connection between devices (computers)
    - Can be both wireless and wired, i.e. connects computers within ethernet network or internet.
   
-   Wireless access point
	- Allow wireless(Wi-Fi) devices to connect to a wired network(generally to the internet), creating **WLANs**.
    
-   Bridge
	- Segments a network, connecting **network segments**.
	- This is done to **improve performance**
	- **ONLY CONNECTS BETWEEN SEGMENTS OF INTERCHANGEABLE PROTOCOLS!**
    
-   Gateway
	- **Modem** + **Firewall** + **Router**
		- **Sends/Receives data**
		- **Filters Data**
		- **Converts data from analogue to digital and vice versa**
    
-   Repeaters
	- Boost the strength of input **electrical** signals 
	- Used to extend the viable length of networks.
    

2.  Explain the main characteristics of wireless transmission media

-   Broadcast radio
	- Small devices that transmit/receive radiowaves
	- **DIFFERENCE: BROADCAST SENDS AUDIO, CELLULAR COMMUNICATES WITH OTHER CELLS.**
    
-   Satellite
	- Large structure in Earth's orbit that transmit and receives **radio waves**
		- Satellite dishes on Earth send/receive data to and from satellites.
	- Very costly!
    
-   Microwave
	- Towers that send data between each other. 
	- Disadvantage is that buildings in between can break transmission, i.e. needs LOS, if LOS is unclear, data can be damaged
    
-   Cellular
	- Tower provides access to multiple mobile devices. This tower connected to another tower, which provides access to other mobile devices, etc.
	- This is called **cellular**, because one tower connected to multiple devices is **one cell**.
	- Transmit/receive **analogue** **radiowaves**.
- WiFi
	- Device that provides access in a small area of connectivity.


3.  What are the problems associated with wired transmission media

-   Twisted pair (UTP, STP)
	- **Ethernet cables are generally 100m viable length!!!**
	- Attenuation(how quickly the signal decreases in strength) is high
	- Thin; break easy
	- Weak against interference
	- Low bandwidth
    
-   Fibre optic (single-mode, multi-mode)
	- Fragile
	- **Very costly**
	- Needs special devices to send/receive data using these cables
	- Short distance only!

4.  Briefly explain the following communications protocols and standards

**Protocols are rules networks use to transfer data**

![](000_Files/Pasted%20image%2020221106201638.png)

-   Wireless (Bluetooth, Ethernet 802.11_x_, RFId, WAP)
	- Sends data via microwaves
	- Max length of Bluetooth is 5m!!
    
-   Wired (Ethernet 802.3)
	- its bs time
    
-   **TCP/IP (IP4, IP6)**
	- See diagram above
	- Application
		- Person A send email to B. The application layer. The data to be sent is found in the application layer
	- Transport 
		- How is the data transferred?
	- Internet
		- Address of device sending + address of device receiving
	- Link
		- Type of transmission media in which this data is sent.

	- Difference between IPv4 and IPv6:
		- v4: 32 bit address
			- Number of ip addresses running out
			- uses 1010
			- Older
		- v6: 128 bit address
			- Uses hexadecimal numbers?
			- uses 1010 + hex
			- Newer
			- **Both used at the same time**


5.  Security of networks

-   Denial of service
	- Networks are given a lot of traffic, which causes the system to be overwhelmed and it crashes.
-   Back doors
	- A method of bypassing normal authentification/encryption in a device, in a way that allows remote, unwanted access to a device and its data.
-   IP spoofing
    ![](000_Files/Pasted%20image%2020221106203213.png)
	- Packets of data are modified(source address is changed) to impersonate other devices, or hide the identity of the actual sender, or both.
	- Commonly used in DDoS attacks.
-   Phishing
	- The fraudulent practice of sending emails purporting to be from reputable companies in order to induce individuals to reveal personal information, such as passwords and credit card numbers

6.  What factors influencing the performance of a network such as

-   Bandwidth
    
-   Network design
    
-   Data collisions
    
-   Excess broadcast traffic.


### CLI Config:
- Connect 2 devices to 1 router using FastEthernet(0/0, 0/1)
- Open Router CLI

- enable
- config t
- hostname Router0
- enable secret **password**
- line con 0
- password **password**
- login
- exit
- line vty 0 4
- password **password**
- login
- exit

- interface FastEthernet0/0
- ip address **ip** **subnet mask**
- no shutdown
- exit
- Repeat last 4 with F.E.0/1

- exit
- exit
- **enter**
- show running-config

Write same ip, subnet mask, default gateway for comps.

### Cisco Diagrams

![](000_Files/Pasted%20image%2020221106191623.png)

### Network Classification
- Geographical Area: PANs, LANs, WANs, etc.
- Design: Peer to peer, **client** to server
	- Client to server is the **most important**
	- Peer to peer works with just simple connections (computer to computer)
- Layout: Topology (Bus, Start, Ring, etc.)
- Protocols: TCP/IP, HTTP, etc.
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
