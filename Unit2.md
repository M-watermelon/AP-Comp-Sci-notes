## Unit 2:

Computer network - type of computing system

- Packet switching -> file split into packets \[sent in any order\], is reassembled by reciever \[done by router \ ] (its small amount of data)
- Bandwidth -> max amount of data that can be sent on network during a fixed amount of time  (bits per second)

DNS Spoofing - Assign different IP addresses for a service that redirects user to a malicious website

### Computer protocol models:

- OSI -> Open systems interconnect: 7 groups of protocols
7\.  Application    [HTTP, DNS]
6\.  Presentation   [TCP, UDP]
5\.  Session   
4\.  Transport
3\.  Network
2\.  Data link 
1\.  Physical

- TCP -> Transmission Control Protocol
  - **Error checking and recovery**
  - Slow
  - Accurate 
  - Three way handshake
  - Email, web browsing
  - Unicast
- UDP -> User Datagram Protocol
  - Fast
  - Inaccurate, does **not** guarantee transfers
  - Music streaming, VolP (Voice over Internet Protocol)
  - Unicast, multicast, broadcast
  - **Error checking only**  <mark>discards erroneous packets</mark>
### TCP/ IP model

- Application    [HTTP, DNS]
  - URL -> Uniform Resource Location
  - Web server: provides web pages to clients
  - http: HyperText Transfer Protocol,   ask and recieve data from web server  **Uses TCP Port 80** 
  - https: secure version of http **Uses TCP Port 443**
  - DNS: Domain Name Service, Connects URL to an IP address
- Transport   [TCP, UDP]
    - Port numbers assigned to devices
- Internet [IP] (OSI level 3)
  - IPV4, 32 bits, 4 octets, 8 bits long
  - Unicast: Specific device, internet-wide access [TCP]
  - Multicast: Group of devices, range of IPs, Internet-wide access [UDP]
  - Broadcast: *All* devices in LAN, data stops at router [UDP]

- Network Access layer [Data link, Fiber, MAC, Ethernet, NIC, Wires]
  - Physical layer, delivers packets from one NIC (Network Interface Card) to another (hop)
  - Each NIC has a unique MAC (Media Access Control) Address [Used for local hops]
  - Packet uses **metadata ** for routing info

- LAN -> Local Area Network 
- AS --> Autonomous systems 
- Intranet --> LANS connected by routers
- IETF -> Internet Engineering Task Force -> develops standards, technical discussions regarding internet
- DHCP -> Dynamic Host Configuration Protocol (Assigns IP addresses)

