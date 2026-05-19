# 🌐 Scalable Secure Network Infrastructure (PTC Inc.)

**Author:** Sara Amjad | **Date:** May 2026  

> **Academic Context:**  
This project was developed as part of Unit 09: Networking under the Pearson BTEC HND in Digital Technologies (Cyber Security). The work demonstrates the design, implementation, and evaluation of a scalable, secure, and efficient enterprise network infrastructure for a simulated organization (PTC Inc.), focusing on performance optimization, security integration, and future scalability.

## 📌 Project Overview
This repository presents a secure and scalable enterprise network design for a simulated global organization, PTC Inc. The system focuses on enabling efficient communication, secure data transfer, and remote accessibility across multiple offices using modern networking technologies.

The proposed infrastructure integrates **star topology architecture**, **5G backup connectivity**, and **SD-WAN principles** to ensure high availability and performance. The design also incorporates **firewalls, VLAN segmentation, VPN access, and QoS mechanisms** to enhance security and traffic optimization.

Cisco Packet Tracer is used to simulate the network environment, including routers, switches, access points, and security configurations.
<p align="center">
  <img src="Images/Network Packet Tracing .png" width="850"/>
</p>

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

The system follows a **star topology design**, where all devices connect to a central switching and routing core for efficient control and scalability.

- **Core Layer:** Router (Gateway, OSPF, BGP, NAT/PAT)  
- **Distribution Layer:** Switches (VLANs, LACP, PoE)  
- **Access Layer:** End devices and wireless access points  

<p align="center">
  <img src="Images/Star Topology.png" width="700"/>
</p>


## 🔄 Network Workflow

- Devices connect via switches and access points  
- Router manages internal and external traffic flow  
- Firewall applies security rules and ACL filtering  
- QoS prioritizes critical services (video calls, cloud apps)  
- VPN enables secure remote access  
- VLANs isolate network traffic for security  


## 🏗 Network Implementation

### ⚙ Router Configuration  
The router acts as the central gateway between LAN and WAN, managing routing, security, and IP allocation.

- Supports OSPF and BGP routing protocols  
- Provides DHCP services for automatic IP assignment  
- Implements NAT/PAT for internet sharing  

<p align="center">
  <img src="Images/Router Configuration .png" width="700"/>
</p>

### 🔀 Switch Configuration  
Switches manage internal communication and VLAN segmentation.

- VLAN 10 → PCs and internal devices  
- VLAN 20 → Access Points  
- LACP enables redundancy and load balancing  
- PoE supports powered network devices  

<p align="center">
  <img src="Images/Switch Configuration .png" width="700"/>
</p>


### 📶 Access Point Configuration  
Wireless access points provide secure connectivity for users.

- Wi-Fi 6 (802.11ax) support  
- WPA3 encryption  
- Static IP configuration for management  


## 🔥 Security Implementation

- 🔐 Firewall with ACL-based filtering  
- 🔑 VPN secured with AES-256 encryption  
- 🧱 VLAN segmentation for isolation  
- 🛡 IDS/IPS for intrusion detection  
- ☁ DMZ for public-facing systems

<p align="center">
  <img src="Images/Virtual Private Network (VPN) .png" width="700"/>
</p>

## 📊 Bandwidth Analysis

- Data Sharing: 5–10 Mbps per user  
- Video Conferencing: 4–6 Mbps per user  
- File Sharing: 10–15 Mbps per user  
- Peak Load: 50–60 Mbps (scalable higher)  

## 📡 IP Addressing Scheme

| Category | IP Range | Description |
|----------|----------|-------------|
| Internal Devices | 192.168.1.0/24 | PCs, printers, internal systems |
| Servers | 10.0.0.0/16 | Static server infrastructure |
| Guest Network | 172.16.0.0/24 | Restricted guest access |
| Public Services | Public IPs | External-facing services |
| Expansion | Reserved subnets | Future scalability |


## 🛠 Maintenance & Scalability

- Daily: Hardware checks and log monitoring  
- Weekly: Firmware updates and backups  
- Monthly: Security audits  
- Quarterly: Infrastructure upgrades  

## 📊 Testing & Validation

- Ping → connectivity testing  
- Traceroute → path analysis  
- SSH → secure remote access
  
<p align="center">
  <img src="Images/Ping Command .png" width="700"/>
</p>

---

<p align="center">
  <img src="Images/Traceroute Command .png" width="700"/>
</p>

---

<p align="center">
  <img src="Images/Secure Shell (SSH) .png" width="700"/>
</p>

---

## 📈 Monitoring & Optimization

- SNMP / NetFlow traffic monitoring  
- IDS/IPS security tracking  
- QoS traffic prioritization  
- Real-time performance monitoring tools  

## ⚠️ Disclaimer

This repository was developed for academic and educational purposes to demonstrate the design and implementation of secure and scalable computer networking systems within a simulated enterprise environment.
