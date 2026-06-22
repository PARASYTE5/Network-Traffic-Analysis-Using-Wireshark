# Network Traffic Analysis Using Wireshark

## Overview
This project demonstrates the use of Wireshark to capture, inspect, and analyze network traffic in a controlled lab environment. The goal was to understand how common network protocols operate and how data is transmitted between devices across a network.

Through packet analysis, key networking concepts such as DNS resolution, TCP connection establishment, ICMP communication, and protocol hierarchy were explored to strengthen foundational networking and cybersecurity knowledge.

---

## Objectives

- Capture live network traffic using Wireshark.
- Analyze common network protocols.
- Understand packet structure and communication flow.
- Examine source and destination IP addresses.
- Study DNS lookups and website communication.
- Develop practical packet analysis and network monitoring skills.

---

## Tools & Environment

**Platform:** Kali Linux

**Tool:** Wireshark

**Protocols Analyzed:**
- DNS
- TCP
- ICMP
- HTTP/HTTPS
- TLS

---

## Methodology

### 1. Packet Capture
- Started a packet capture session on the active network interface.
- Generated traffic by browsing websites and using network utilities.

### 2. DNS Analysis
- Captured DNS query and response packets.
- Identified domain name resolution processes.
- Examined IP addresses returned by DNS servers.

### 3. TCP Handshake Analysis
- Investigated TCP connection establishment.
- Observed the three-way handshake process:
  - SYN
  - SYN-ACK
  - ACK

### 4. ICMP Analysis
- Generated ICMP traffic using ping commands.
- Examined Echo Requests and Echo Replies.
- Studied how ICMP assists in network diagnostics.

### 5. Protocol Hierarchy Review
- Used Wireshark's Protocol Hierarchy Statistics feature.
- Analyzed the distribution of network protocols within captured traffic.

---

## Key Findings

- DNS traffic revealed how domain names are translated into IP addresses.
- TCP packets demonstrated reliable communication through the three-way handshake process.
- ICMP traffic showed network reachability and connectivity testing mechanisms.
- HTTPS/TLS traffic highlighted encrypted communication between clients and servers.
- Protocol hierarchy statistics provided insights into network traffic composition.

---

## Skills Demonstrated

- Network Traffic Analysis
- Packet Inspection
- Protocol Analysis
- Network Monitoring
- DNS Investigation
- TCP/IP Fundamentals
- Wireshark Usage
- Security Documentation

---

## Conclusion

This project provided hands-on experience in network packet analysis using Wireshark. By examining DNS, TCP, ICMP, and HTTPS traffic, a deeper understanding of network communication and protocol behavior was achieved. The project strengthened practical networking and cybersecurity skills while demonstrating the ability to analyze and document network activity effectively.

---

## Future Improvements

- Analyze ARP traffic and MAC address resolution.
- Investigate TLS certificate exchanges.
- Capture traffic from multiple devices.
- Explore suspicious traffic detection techniques.
- Perform comparative analysis of different network protocols.
