# 🌐 Enterprise Multi-Branch Network Infrastructure using Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates the design and implementation of a real-world enterprise multi-branch network using Cisco Packet Tracer. The network consists of four branch offices interconnected through a Core Layer 3 Switch using OSPF dynamic routing. Each branch contains multiple departments connected through VLANs with centralized routing, DHCP, wireless connectivity, and inter-branch communication.

The objective of this project is to simulate an enterprise network environment similar to those used in corporate organizations.

---

# 🏢 Branch Offices

- 🏢 Head Office (R1)
- 🏢 Branch Office 1 (R2)
- 🏢 Branch Office 2 (R3)
- 🏢 Branch Office 3 (R4)

Each branch contains:

- HR Department
- Finance Department
- Admin Department
- Employee Department
- Wireless Access Point
- Cisco Router
- Cisco Switch

---

# 🛠 Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- Cisco Router 2911
- Cisco Catalyst 2960 Switch
- Cisco Multilayer Switch
- VLAN Configuration
- IEEE 802.1Q Trunking
- Router-on-a-Stick
- DHCP
- Dynamic Routing (OSPF)
- Layer 3 Switching
- Wireless Access Points
- Inter-VLAN Routing
- Enterprise WAN Design

---

# 🌍 Network Architecture

Each branch consists of:

- 1 Cisco Router
- 1 Layer 3 Core Connection
- 2 Access Switches
- 4 VLANs
- Wireless Access Point
- Multiple End Devices

The four branch routers communicate through a Core Layer 3 Switch using OSPF Area 0.

---

# 📡 VLAN Configuration

| VLAN | Department |
|------|------------|
| VLAN 10 | HR |
| VLAN 20 | Finance |
| VLAN 30 | Admin |
| VLAN 40 | Employee |

---

# 🌐 IP Addressing Plan

## R1 (Head Office)

| VLAN | Network |
|------|----------------|
| VLAN 10 | 192.168.10.0/24 |
| VLAN 20 | 192.168.11.0/24 |
| VLAN 30 | 192.168.12.0/24 |
| VLAN 40 | 192.168.13.0/24 |

---

## R2

| VLAN | Network |
|------|----------------|
| VLAN 10 | 172.1.0.0/16 |
| VLAN 20 | 172.2.0.0/16 |
| VLAN 30 | 172.3.0.0/16 |
| VLAN 40 | 172.4.0.0/16 |

---

## R3

| VLAN | Network |
|------|----------------|
| VLAN 10 | 173.1.0.0/16 |
| VLAN 20 | 173.2.0.0/16 |
| VLAN 30 | 173.3.0.0/16 |
| VLAN 40 | 173.4.0.0/16 |

---

## R4

| VLAN | Network |
|------|----------------|
| VLAN 10 | 193.168.10.0/24 |
| VLAN 20 | 193.168.20.0/24 |
| VLAN 30 | 193.168.30.0/24 |
| VLAN 40 | 193.168.40.0/24 |

---

# 🔀 Routing Protocol

Dynamic routing is implemented using:

- OSPF (Open Shortest Path First)
- Area 0 Backbone

All branch routers exchange routing information through the Core Layer 3 Switch.

---

# 📶 Wireless Network

Each branch includes:

- Wireless Access Point
- DHCP Address Assignment
- Wireless Client Connectivity

---

# ✨ Features Implemented

- Enterprise Multi-Branch Topology
- VLAN Segmentation
- Router-on-a-Stick
- Inter-VLAN Routing
- DHCP Configuration
- OSPF Dynamic Routing
- Layer 3 Core Switching
- Wireless Access Point Integration
- Automatic Route Advertisement
- Enterprise Network Design
- End-to-End Branch Communication

---

# 🧪 Verification

The following tests were successfully performed:

- VLAN Verification
- Trunk Verification
- DHCP Address Assignment
- OSPF Neighbor Formation
- Routing Table Verification
- Branch-to-Branch Connectivity
- End Device Communication
- Wireless Connectivity

---

# 📷 Project Screenshots

- Enterprise Network Topology
- VLAN Configuration
- Trunk Configuration
- DHCP Configuration
- OSPF Neighbors
- Routing Table
- Wireless Access Point
- Successful Ping Tests

---

# 💼 Skills Demonstrated

- Enterprise Network Design
- Cisco Routing
- Cisco Switching
- VLAN Implementation
- DHCP Configuration
- Dynamic Routing (OSPF)
- Layer 3 Switching
- Router-on-a-Stick
- Wireless Networking
- Cisco IOS CLI
- Network Troubleshooting
- Network Documentation

---

# 🚀 Future Enhancements

- Access Control Lists (ACL)
- NAT/PAT
- SSH Remote Management
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection
- EtherChannel
- HSRP
- Firewall Integration
- Cloud Connectivity (AWS/Azure)

---

# 🎯 Learning Outcome

This project demonstrates the deployment of a scalable enterprise network using Cisco technologies. It combines Layer 2 switching, Layer 3 routing, dynamic routing, DHCP, VLAN segmentation, and wireless networking into a single integrated infrastructure, providing hands-on experience with enterprise networking concepts commonly used in production environments.

---

## 👨‍💻 Author

**Muni Sai Divith K**

**B.E. Computer Science & Engineering (Cyber Security)**

**Networking | Cloud | Cyber Security**
