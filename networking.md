   **Cloud computing can be specified**
   -----------------------
**| NETWORKING |**
--------------------------  
# ****TYPES OF NETWORK****
- **Personal Area Network (PAN)**
- **Local Area Network (LAN)**
- **Campus Area Network (CAN)**
- **Metropolitan Area Network (MAN)**
- **Wide Area Network (WAN)**
- ---------
# >***LOAD BALANCER --Distribution of set of task over a set of resources***
  ## TCP -IP MODEL -- a framework for organizing the set of communication protocols used in the Internet and similar computer networks
  ***It loosely defines a four-layer model***
-   layer 1 -   ***Application layer***--> create user data and communicate this data to other applications on another or the same host.This is the layer in which all application protocols, such as SMTP, FTP, SSH, HTTP, operate
-    layer 2 -   ***Transport layer***--> provides a channel for the communication needs of applications. UDP is the basic transport layer protocol, providing an unreliable connectionless datagram service
-  layer 3 -   ***Internet Layer***--> This layer defines the addressing and routing structures used for the TCP/IP protocol suite. The primary protocol in this scope is the Internet Protocol, which defines IP addresses.
-    layer 4 -   ***Link Layer***--> includes the protocols used to describe the local network topology and the interfaces needed to affect the transmission of internet layer datagrams to next-neighbor hosts. 
   ---------------
   **SMARTNICs**
   - *SmartNICs offload packet processing tasks from server CPUs, freeing up resources for application performance. They can run packet capture and load balancing, among other tasks*
   *A SmartNIC is a type of NIC card and programmable accelerator that makes data center networking, security, and storage efficient and flexible*
- Networking: A SmartNIC is capable of running functions like routing, fireballing, telemetry, load balancing, and overlay networks. All of this is processed by the SmartNICs CPU, reducing the load on the host server's CPU. This leaves room for other applications to run without overload.
- - DPDK (Data Plane Development Kit): A framework (under the Linux Foundation) comprised of various userspace libraries and drivers for fast packet processing.
  -  - Fast-Path (Kernel bypass)
  -  - Poll Mode Driver
- - SR-IOV : Single Root I/O Virtualization (SR-IOV) is the complex name for a technology beginning to find its way into embedded devices. SR-IOV is a hardware standard that allows a PCI Express device – typically a network interface card (NIC) – to present itself as several virtual NICs to a hypervisor. 


-----

   
                                  
  ## OSI MODEL -- provides a common basis for the coordination of standards development for the purpose of systems interconnection
  ***Layer Architecture***
-    layer 1 - ***Physical Layer***-->responsible for the transmission and reception of unstructured raw data between a device, such as a network interface controller, Ethernet hub, or network switch, and a physical transmission medium.
-  layer 2 - ***Data Link***-->  node-to-node data transfer—a link between two directly connected nodes.[Node-a redistribution point or a communication endpoint.] It defines the protocol to establish and terminate a connection between two physically connected devices. It also defines the protocol for flow control between them.
-   layer 3 - ***Network Layer***--> provides the functional and procedural means of transferring packets from one node to another connected in "different networks". 
-   layer 4 - ***Transport Layer***--> The transport layer provides the functional and procedural means of transferring variable-length data sequences from a source host to a destinationhost from one application to another across a network, while maintaining the quality-of-service functions Breaking large protocol data units or long data streams into smaller chunks called "segments".The process of dividing data into segments is called segmentation                             
-   layer 5 - ***session Layer***--> The session layer creates the setup, controls the connections, and ends the teardown, between two or more computers, which is called a "session"
-  layer 6 - ***Presentation Layer***--> handles protocol conversion, data encryption, data decryption, data compression, data decompression, incompatibility of data representation between operating systems, and graphic commands
-  layer 7 - ***Application Layer***-->functions typically include file sharing, message handling, and database access, throughthe most common protocols at the application layer, known as HTTP, FTP, SMB/CIFS, TFTP, and SMTP
  ----
                            *LAYER 4 AND LAYER 7 ARE THE ESSENTIALS FOR THE NETWORKING*
----
![image](https://github.com/Rudrakshrawal/Keywords/assets/144530387/c01fbe45-22f4-4cbe-85aa-047ebcca82ac)

---------------
*NAT-(Network address translation) a method of mapping an IP address space into another by modifying network address information in the IP header of packets while they are in transit across a traffic routing device.*
- ****STATIC NAT**** : allows the user to configure one-to-one translations of the inside local addresses to the outside global addresses. It allows both IP addresses and port number translations from the inside to the outside traffic and the outside to the inside traffic.
- ****DYNAMIC NAT**** :does the mapping of a local address to a global address happens dynamically. This means that the router dynamically picks an address from the global address pool that is not currently assigned.
- ****PAT(PORT ADDRESS TRANSLATION)**** :Port Address Translation (PAT) is a function that allows multiple devices on a private network to share a single public IP address

# ROUTING ---> The process of selecting a path for traffic in a network or between or across multiple networks.
  ![image](https://github.com/Rudrakshrawal/Keywords/assets/144530387/fa219439-0eca-4beb-b190-7acfe1f2fdec)
#TYPES 
![image](https://github.com/Rudrakshrawal/Keywords/assets/144530387/fefa2fee-8dd4-4a9f-bcb5-aef40c306178)

- Static Routing
- Default Routing
- Dynamic Routing
--------------------------
  **Main Routing Protocols**
  - Routing Information Protocol
  - Open Shortest Path First protocol
  - External gateway protocols
  - Border Gateway Protocol
-------------------
**Algorithms used**
- Distance vector routing
- Link state routing
--------------
*Cloud Routing*
- Dynamically manages connections between two virtual cloud networks or between a cloud network and an on-premises network using the Border Gateway Protocol (BGP).
----
*DNS Routing*
- Translates human-readable domain names (for example, www.amazon.com) to machine-readable IP addresses (for example, 192.0.2.44).
-----------
**Tools used for routing**
- *Transit Gateway* acts as a cloud router and connects VPCs and on-premises networks through a central hub. As your network grows, the complexity of managing incremental connections doesn’t slow you down. When building global applications, you can connect multiple AWS Transit Gateways by using inter-Region peering.
- *Route 53* is a highly available and scalable cloud DNS web service. It provides a reliable and cost-effective way for businesses and developers to route their end users to internet applications.Route 53 Traffic Flow makes it easy for you to manage traffic globally through a variety of routing types to create low-latency, fault-tolerant architectures.
  ![image](https://github.com/Rudrakshrawal/Keywords/assets/144530387/67a62547-15b0-43fa-992a-30aa8aea881b)

  





# Computer Architecture Network
*physical and logical design of the software, hardware, protocols, and media of the transmission of data*
- P2P(peer to peer)
- Client Server Network






------


- <^>NTP- Network Time Protocol (NTP) is an internet protocol that synchronizes computer clock time sources in a network. NTP is one of the oldest parts of the TCP/IP suite. It runs on User Datagram Protocol (UDP), which in turn runs on IP.
- <^>PTP- Precision Time Protocol (PTP) is a protocol that synchronizes clocks in a computer network. It's similar to Network Time Protocol (NTP), but PTP is more accurate, measuring in nanoseconds. PTP is used to synchronize clocks in systems that require precise time synchronization
  
![image](https://github.com/Rudrakshrawal/Keywords/assets/144530387/4d2d5401-cb88-47c3-bf14-14adf5cfe3a9)



  
