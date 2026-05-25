## 🌐 Small Enterprise Network Design using Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates the design and configuration of a small enterprise network using Cisco Packet Tracer.

The network enables inter-departmental communication through routers and switches, implements VLSM-based subnetting, configures routing protocols, and ensures secure remote access and internet connectivity using NAT and DNS.

---

## 🎯 AIM

To design, configure, and test a small enterprise network that:

- Connects multiple departments via routers and switches
- Implements subnetting using VLSM
- Configures routing protocols (Static & Dynamic)
- Enables secure remote management using Telnet
- Implements NAT for external communication

---
<img width="1390" height="1094" alt="image" src="https://github.com/user-attachments/assets/90fa75e1-0b94-46f5-8c41-228d58656a6b" />


## 🚀 Features Implemented

- Variable Length Subnet Masking (VLSM)
- Router Configuration (LAN & WAN interfaces)
- Static Routing
- Dynamic Routing (RIP / EIGRP / OSPF)
- NAT Configuration (Inside & Outside)
- DNS Server Configuration
- Switch Configuration
- End-to-End Connectivity Testing (Ping verification)

---

## 🏢 Network Topology

The enterprise network consists of:

- Multiple departmental LANs
- Core Router
- Switches for internal communication
- DNS Server
- External Network (simulated Internet)
- NAT-enabled router for outside access

---

## 🛠 Technologies Used

- Cisco Packet Tracer
- Routing Protocols: Static, RIP, EIGRP, OSPF
- Telnet for Remote Management
- NAT (Network Address Translation)
- VLSM Subnetting
- DNS Configuration

---

## 📊 VLSM Implementation

VLSM was used to efficiently allocate IP addresses based on departmental requirements.

Steps followed:

- Calculated host requirements per department
- Allocated subnets in descending order
- Assigned network IDs, broadcast addresses, and usable IP ranges
- Configured router interfaces accordingly

---

## 🔄 Routing Configuration

### Static Routing

Manually configured routes for specific network paths.

### Dynamic Routing

Configured routing protocols such as:

- RIP
- EIGRP
- OSPF

Ensured automatic route updates and scalability.

---

## 🌍 NAT Configuration

- Configured Inside and Outside interfaces
- Enabled internet access for internal networks
- Used NAT to translate private IP addresses to public IP addresses

Example:

ip nat inside  
ip nat outside  
ip nat inside source list 1 interface serial 0/0/0 overload  

---

## 🌐 DNS Configuration

- Configured DNS server
- Mapped domain names to IP addresses
- Verified name resolution using ping commands

---

## 🔐 Telnet Configuration

Enabled remote management of routers using Telnet:

line vty 0 4  
password cisco  
login  
transport input telnet  

---

## ✅ Testing & Verification

- Ping between departments
- Ping to external network
- DNS name resolution test
- Routing table verification (show ip route)
- NAT verification (show ip nat translations)

---

## 📂 How to Run the Project

1. Open Cisco Packet Tracer
2. Load the .pkt file
3. Switch to Simulation Mode (optional for testing)
4. Use ping command to verify connectivity

---

## 📈 Learning Outcomes

- Understood enterprise network architecture
- Applied VLSM subnetting practically
- Configured routers and switches
- Implemented static & dynamic routing
- Configured NAT and DNS
- Verified full network connectivity

---

## 👩‍💻 Author

Vanya Nain  
B.Tech CSE
