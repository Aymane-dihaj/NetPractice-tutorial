# Netpractice

- **TCP/IP:**
    - TCP/IP network   model **is a set of protocols** that make connection possible between computers
    - TCP is highly reliable but slow

- **TCP :**
    - TCP stands for **Transmission Control Protocol**. It is a communication standard that enables application programs and devices to exchange messages over a network. It is used to send packets across the internet.
    - TCP **ensures the integrity of the data being communicated over a network**. before it transmits data, TCP establishes a connection between a source and it’s destination, which remains active until communication begins. it **then breaks large amount of data into smaller packets**, while ensuring end-to-end delivery without loss of any data.
    

- **TCP/IP layers:**

![TCP_Model_2.webp](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bceaf66c-4b2a-4303-9fa8-dd2216ab3b12/TCP_Model_2.webp)

- Note:
    - going down the stack is called **encapsulating**
    - going up the stack is called **de-capsulation**

- **IP Address (Network layer):**
    - IP stands for (internet protocol) is part of an internet protocol suite, which also includes the transmission control protocol. together, these two are know as TCP/IP. The internet protocol suite governs rules for packetizing, addressing , transmitting, routing, and receiving data over networks.
    - IP addressing is a logical means of assigning addresses to devices on a network. each device connected to the internet requires a unique IP address.
    - an IP address has two parts; one part identifies the host such as a computer or other device, and the other part identifies the network it belongs to. TCP/IP uses a subnet mask to separate them.
    
- **Host:**
    - **Hosts** are any device which **sends** or **receive** traffic
    - Ex: Computer | laptop | phones | servers
    - Also any Internet of things (IoT) devices ( Tv ,  Speakers , Smart Watches …)
    - Host can be a client or an server
        - Client initiate requests, server respond

- **Server:**
    - Server are simply computers with software installed which **responds** to specific requests.
    
- **Subnet Mask:**
    - A subnet mask is a 32bit (4 bytes) address used to specifies between a network address and host address in the IP address. it defines the range of IP addresses that can be used within a network or a subnet.
    
- **Switch:**
    - A switch connects multiple devices together in a single network. Unlike a router, the switch does not have any interfaces since it only distribute packets to its local network, and cannot talk directly to a network outside of its own.
    
- **Router:**
    - just as the switch connects multiple devices on a single network, the router connects multiple networks together. The router has an interface for each network it connects to.
    - since the router separates different networks , the range of possible IP address on one of its interfaces must not overlap with the range of its other interfaces. An overlap in the IP address range would imply that the interfaces are on the same network.
    
- **Routing table:**
    
    ![routing_table1.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/02f4c91c-60de-4586-92f3-93a20af6239a/routing_table1.png)
    
    - Think of a routing table as a map that **helps routers figure out where to send data packets**. Just like you use a map to find the best route to a destination, a routing table helps routers decide the best path for data to reach its intended location.
        - **Destination:**
            
            The destination specifies a network address on which a host is the end target of the packets. the route that takes effect when no other route is available for an IP destination address. The default route will use the next-hop address to send the packets on their way without giving a specific destination.
            
            The default route will match any network.
            
        - Next hop:
            
            The next hop is the next network device or router that a data packet should be forwarded to in order to reach its destination. When a router consults its routing table to determine the path for a packet, it identifies the next hop as  the specific network interface or IP address of the next router to which the packet should be sent.
            
            ✏️ **By Nozel.**
