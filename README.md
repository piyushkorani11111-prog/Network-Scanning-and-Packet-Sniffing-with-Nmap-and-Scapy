# Network-Scanning-and-Packet-Sniffing-with-Nmap-and-Scapy
This repository contains a Sample of Network and Port Scanning Techniques used by Nmap and Scapy drafted as an assignment given by ParoCyber Ethical Hacking Program.

# Repository Overview
This repository documents the practical application of fundamental network security tools: Nmap (for host discovery, port scanning, and service detection) and Scapy (for network packet crafting, sending, and analysis). This project reproduces class demonstrations to reinforce core concepts in network communication and defense.

# Objective
The primary goals of this lab assignment were to:

* Reproduce Core Nmap Functionality: Successfully execute various Nmap scan types to understand the underlying networking principles of host discovery,
  service enumeration, and OS detection.
* Master Scapy for Packet Manipulation: Practice crafting, sending, sniffing, and analyzing network packets at different layers
  (e.g., ARP, IP, TCP) to gain a deeper understanding of protocol behavior.
* Create Professional Documentation: Document all commands, code snippets, and analysis results in a clean, organized, and professional GitHub repository structure.

# Prerequisites and Setup
Before executing the commands and scripts documented in this repository, ensure the following tools are installed and configured on your testing environment 
(e.g., Kali Linux, Parrot OS, or a VM with necessary tools).

1. **Lab Enviorment**
  * Operating System	(e.g., Kali Linux 2023.4 / Ubuntu 22.04)
  * Nmap Version	(e.g., Nmap version 7.94)
  * Python Version	(e.g., Python 3.10+)
  * Scapy Version	Install via pip install scapy


2. **Lab Network Simulation**

   All exercises were performed within a controlled, isolated lab environment (Virtual Machine network) to ensure no external, third-party systems were affected.
      * Lab Network Range: (192.168.10.0/24).
      * Target Machine Pseudo IP: (192.168.10.50) (Used as a placeholder for the intentionally vulnerable or test host within the lab).
      * Attacker Machine Pseudo IP: (192.168.10.10).

        2.1 NMAP Scans
        
        This section documents the execution and results of various Nmap scan types, demonstrating different levels of network reconnaissance.

        2.1.1 **Host Discovery Scans**
        <img width="1063" height="315" alt="image" src="https://github.com/user-attachments/assets/af90144a-a284-4b5d-a759-2127268123a6" />

        2.1.2 **Port Scanning Techniques**
        <img width="1066" height="523" alt="image" src="https://github.com/user-attachments/assets/c76b24ec-b620-49fa-9445-3b94d66b9f16" />

        2.1.3 **Advanced Probing and Detection**
        <img width="1043" height="422" alt="image" src="https://github.com/user-attachments/assets/c22ebc12-5d02-4fc0-99b3-0a007299f6c6" />

        2.2 Scapy Packet Crafting and Analysis

        This section documents the creation and execution of custom Python scripts using the Scapy library to interact with network protocols at a low level.

        2.2.1 **TCP SYN Packet Crafting (Simple Port Scan)**

        This demonstrates Layer 3 (IP) and Layer 4 (TCP) communication by crafting a basic TCP SYN packet to check the status of port 80 on the target.
        <img width="1056" height="518" alt="image" src="https://github.com/user-attachments/assets/0d1ca3bb-72c8-48d7-9862-11657666337d" />

        2.2.2 **Packet Sniffing**

        This demonstrates using Scapy's built-in sniffing functionality to passively monitor the network interface for specific protocols (e.g., ICMP).
        <img width="1048" height="371" alt="image" src="https://github.com/user-attachments/assets/1dd47b74-02ab-4f7a-bf8f-bbc144f583fc" />
   
        2.2.3 **ARP Packet Crafting (Host Discovery)**

        This demonstrates using Layer 2 communication to discover the MAC address of the target host (192.168.10.50).
        <img width="1071" height="447" alt="image" src="https://github.com/user-attachments/assets/3a4006da-57d3-4ca6-ba59-8653093e3a51" />

# Conclusion
This assignment successfully demonstrated the hands-on use of Nmap and Scapy, bridging theoretical knowledge of networking protocols with practical execution. The ability to craft specific packets and interpret scan results is essential for both defensive security analysis and ethical hacking methodologies.
