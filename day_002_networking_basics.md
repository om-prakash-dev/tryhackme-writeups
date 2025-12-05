2. 📅 Day 002: Networking Fundamentals (TryHackMe: What is Networking?)

Goal: Understand the fundamental architecture of how computers communicate. This is the foundation upon which all cybersecurity attacks and defenses are built.

1. The OSI Model (7-Layer Conceptual Framework)

Purpose: A conceptual model used to describe how data moves through a network, breaking down complex interactions into manageable layers. 

The Seven Layers (Bottom Up):

Physical (Layer 1): Cables, signals, hardware (e.g., RJ45, fiber). Handles the raw bit stream.

Data Link (Layer 2): MAC addresses, Switches (e.g., Ethernet). Manages node-to-node data transfer.

Network (Layer 3): IP addresses, Routers (e.g., IPv4, ICMP). Handles logical addressing and routing across networks.

Transport (Layer 4): Segmentation, flow control (e.g., TCP, UDP). Provides reliable (TCP) or unreliable (UDP) data transmission.

Session (Layer 5): Connection management (e.g., establishing, managing, and terminating sessions).

Presentation (Layer 6): Data encryption/format (e.g., SSL/TLS, ASCII, JPEG). Translates data for the Application layer.

Application (Layer 7): User interaction (e.g., HTTP, SMTP, DNS, FTP). The interface used by network applications.

2.  The TCP/IP Model (4-Layer Practical Model)

Purpose: A simplified model used in the real world (the model the internet runs on). 

The Four Layers:

Network Access (L1/L2 Combined): Handles physical transmission (like OSI L1 & L2).

Internet (L3): Responsible for routing of data packets (like OSI L3).

Transport (L4): Handles data communication between hosts (like OSI L4).

Application (L5-L7 Combined): Protocols used by applications (like OSI L5, L6, & L7).

3. Key Protocols (The Rules of Communication)

ARP (Address Resolution Protocol): Operates at the Data Link layer (L2). Its function is to map an IP address (logical address) to a MAC address (physical address) on a local network.

DHCP (Dynamic Host Configuration Protocol): Operates at the Application layer (L7). This protocol is responsible for automatically assigning IP addresses and other network configuration parameters to devices joining a network.

DNS (Domain Name System): Operates at the Application layer (L7). DNS is essential for translating human-readable domain names (like https://www.google.com/search?q=google.com) into numerical IP addresses that computers use to communicate.

HTTP (Hypertext Transfer Protocol): Operates at the Application layer (L7). This is the fundamental protocol used for transmitting web pages and data over the internet.

4. IP Addressing Basics

IPv4 Definition: A 32-bit numerical address (e.g., 192.168.1.1) used for identifying devices and routing traffic.

Private IP Ranges (Non-Routable on the Internet):

Class A: 10.0.0.0 to 10.255.255.255

Class B: 172.16.0.0 to 172.31.255.255

Class C: 192.168.0.0 to 192.168.255.255
