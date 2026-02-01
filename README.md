# Packet Sniffing and Analysis Using Wireshark

## Project Title
Packet Sniffing and Analysis Using Wireshark

## Project Description
This project demonstrates how packet sniffing and network traffic analysis can be performed using **Wireshark**.  
The purpose of the project is to understand how data flows through a network, analyze protocol behavior, and identify security risks in unencrypted communication.

The project focuses on:
- Capturing live network traffic
- Analyzing TCP and UDP protocols
- Visualizing traffic using I/O Graphs
- Demonstrating security vulnerabilities in HTTP
- Understanding the importance of HTTPS/TLS encryption

This project was developed for the **Information Security** course (Fall 25-26).

---

## Objectives
- Capture real-time packets from a network interface
- Analyze the TCP 3-Way Handshake
- Compare TCP and UDP traffic patterns
- Identify plain-text credential leakage in HTTP
- Use statistical tools such as Protocol Hierarchy and I/O Graphs

---

## Tools & Technologies
- **Wireshark**
- Web Browser (traffic generation)
- Local Area Network (Wi-Fi)
- Operating System: Windows

---

## Experiments Performed

### 1️. Live Packet Capture
- Selected active network interface
- Enabled promiscuous mode
- Captured TCP, UDP, DNS, HTTP, and TLS traffic

---

### 2️. TCP 3-Way Handshake Analysis
The TCP connection establishment process was analyzed using display filters:

- SYN
- SYN-ACK
- ACK

This shows how reliable communication is established between client and server.

---

### 3️. HTTP Credential Sniffing
An unencrypted HTTP login was captured to demonstrate security risks.

- HTTP POST request was filtered
- Username and password were visible in plain text
- This proves HTTP is insecure

---

### 4️. Protocol Hierarchy
- Identified protocol distribution
- Observed TCP dominance
- Analyzed UDP usage (DNS traffic)

---

### 5️. I/O Graph Analysis
- Visualized traffic flow over time
- Compared TCP vs UDP behavior
- Observed continuous UDP packets and controlled TCP packets

---

## Key Findings
- TCP is reliable but slower due to acknowledgments
- UDP is faster but unreliable
- HTTP exposes sensitive information
- HTTPS/TLS is essential for secure communication

---

## Repository Structure
