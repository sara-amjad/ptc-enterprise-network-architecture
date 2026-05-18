# 🌐 Scalable Secure Network Infrastructure (PTC Inc.)

**Author:** Sara Amjad | **Date:** May 2026  

> **Academic Context:**  
This project was developed as part of Unit 09: Networking under the Pearson BTEC HND in Digital Technologies (Cyber Security). The work demonstrates the design, implementation, and evaluation of a scalable, secure, and efficient enterprise network infrastructure for a simulated organization (PTC Inc.), focusing on performance optimization, security integration, and future scalability.

## 📌 Project Overview
This repository presents a secure and scalable enterprise network design for a simulated global organization, PTC Inc. The system focuses on enabling efficient communication, secure data transfer, and remote accessibility across multiple offices using modern networking technologies.

The proposed infrastructure integrates **star topology architecture**, **5G backup connectivity**, and **SD-WAN principles** to ensure high availability and performance. The design also incorporates **firewalls, VLAN segmentation, VPN access, and QoS mechanisms** to enhance security and traffic optimization.

Cisco Packet Tracer is used to simulate the network environment, including routers, switches, access points, and security configurations.

## 🧠 Key Features

- 🌐 Scalable enterprise network design (200+ devices support)  
- 🔐 Secure communication using firewall, ACLs, and VPN  
- ⚙ Star topology-based architecture for centralized control  
- 📡 VLAN segmentation for traffic isolation  
- 🚀 QoS implementation for traffic prioritization  
- 📶 5G backup and SD-WAN integration for reliability  
- 🖧 Static & dynamic routing (OSPF, BGP)  
- ☁ Cloud-ready and remote-access enabled infrastructure  

## 🏗 Network Architecture

The system follows a **star topology design**, where all devices connect to a central switch/router for efficient management and scalability.

- Core Layer: Router (Gateway, OSPF, BGP, NAT)  
- Distribution Layer: Switches (VLANs, LACP, PoE)  
- Access Layer: PCs, servers, and wireless access points  

## 🔄 Network Workflow

1. 📡 Devices connect through switches and access points  
2. 🌐 Router manages internal and external traffic  
3. 🔐 Firewall enforces security policies and ACL rules  
4. 📊 QoS prioritizes critical traffic (video, cloud apps)  
5. ☁ VPN enables secure remote access  
6. 🖧 Data flows through segmented VLAN architecture  

## 🏗 Network Implementation

### ⚙ Router Configuration
- Acts as gateway between LAN and WAN  
- Supports OSPF/BGP routing protocols  
- Provides DHCP services for IP allocation  
- Implements NAT/PAT for public access sharing  

📌 **Figure 1: Router Configuration**


### 🔀 Switch Configuration
- VLAN 10: Internal PCs  
- VLAN 20: Access Points  
- LACP enabled for redundancy  
- PoE support for IP devices  

📌 **Figure 2: Switch Configuration**

### 📶 Wireless Access Points
- Wi-Fi 6 (802.11ax) enabled  
- WPA3 encryption for secure access  
- RADIUS authentication support  

📌 **Figure 3: Wireless Access Point Setup**

### 🔥 Firewall & Security
- ACL-based traffic filtering  
- VPN secure remote access (AES-256)  
- IDS/IPS monitoring for threats  

📌 **Figure 4: Firewall Configuration**

### 📊 Bandwidth Analysis
The network is designed to handle:

- Data Sharing: 5–10 Mbps per user  
- Video Conferencing: 4–6 Mbps per user  
- File Sharing: 10–15 Mbps per user  
- Peak Load Capacity: 50–60 Mbps+ scalable to 10 Gbps  

📌 **Figure 5: Bandwidth Requirement Graph**


### 🗺 Network Topology
Star topology ensures:
- Centralized control  
- Easy scalability  
- Fault isolation  

📌 **Figure 6: Star Topology Diagram**

### 🔄 Deployment Flowchart
Pre-installation and post-installation process includes:
- Requirement analysis  
- Topology selection  
- Configuration & deployment  
- Testing & optimization  

📌 **Figure 7: Network Deployment Flowchart**

## 🔐 Security Considerations

- 🔒 VPN for secure remote access  
- 🔥 Firewall with ACL rules  
- 🧱 VLAN segmentation for isolation  
- 🛡 IDS/IPS for threat detection  
- 🔑 MFA authentication for users  
- ☁ DMZ for public-facing services  


## 📡 IP Addressing Scheme

| Category | IP Range | Description |
|----------|----------|-------------|
| Internal Devices | 192.168.1.0/24 | PCs and local devices |
| Servers | 10.0.0.0/16 | Static server IPs |
| Guest Network | 172.16.0.0/24 | Restricted access |
| Public Services | Public IPs | External services |
| Expansion | Reserved | Future scalability |

📌 **Figure 8: IPv4 / IPv6 Addressing Visualization**


## 🛠 Maintenance & Scalability

- 📅 Daily: Hardware and log checks  
- 📅 Weekly: Firmware updates and backups  
- 📅 Monthly: Security audits and performance checks  
- 📅 Quarterly: Infrastructure upgrade and scalability planning  

📌 **Figure 9: Maintenance Schedule**

## 📊 Testing & Validation

- ✔ Ping test for connectivity verification  
- ✔ Traceroute for path analysis  
- ✔ SSH for remote administration  
- ✔ Performance monitoring under load  

📌 **Figure 10: Network Testing (Ping / Traceroute)**

## 📈 Monitoring & Optimization

- SNMP / NetFlow monitoring  
- IDS/IPS security tracking  
- QoS traffic prioritization  

## ⚠️ Disclaimer
This repository was developed for academic and educational purposes to demonstrate the design and implementation of secure and scalable computer networking systems within a simulated enterprise environment.
