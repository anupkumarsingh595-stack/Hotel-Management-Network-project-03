# Hotel-management-network__Project_Lab_03
<!--  ██████  ██████  ███    ██  █████  -->
<!--  CCNA NETWORKING PROJECT README   -->

<h1 align="center">🏨 Hotel Management Network</h1>

<p align="center">
  <b>CCNA-Level Enterprise Network | Cisco Packet Tracer | VLANs | OSPF | DHCP | Security</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CCNA-Networking-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Cisco-Packet%20Tracer-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/VLAN-Implementation-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OSPF-Routing-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Network-Security-red?style=for-the-badge"/>
</p>

---

## 📌 Project Overview

This project demonstrates the **design and implementation of a three-floor hotel management network** using **Cisco Packet Tracer**, following **CCNA-level enterprise networking principles**.

The network is designed to ensure:
- Departmental separation
- Secure communication
- Scalability
- Real-world configuration practices

---

## 🏢 Network Structure

- **1st Floor:** Reception, Store, Logistics  
- **2nd Floor:** Finance, HR, Sales  
- **3rd Floor:** IT, Admin  

Each floor contains:
- One switch
- One router (Router-on-a-Stick)
- Wired and wireless end devices

Routers are interconnected using **WAN serial links**.

---

## 🧩 Technologies & Concepts Used

- **VLANs** – Department-level network segmentation  
- **Router-on-a-Stick** – Inter-VLAN routing  
- **OSPF (Area 0)** – Dynamic routing protocol  
- **DHCP** – Automatic IP address allocation  
- **SSH** – Secure remote device management  
- **Port Security** – Sticky MAC-based access control  
- **WAN /30 Subnetting** – Efficient point-to-point links  

---

## 🌐 VLAN & IP Addressing Plan

| Department | VLAN | Network |
|-----------|------|---------|
| IT | 10 | 192.168.1.0/24 |
| Admin | 20 | 192.168.2.0/24 |
| Sales | 30 | 192.168.3.0/24 |
| HR | 40 | 192.168.4.0/24 |
| Finance | 50 | 192.168.5.0/24 |
| Logistics | 60 | 192.168.6.0/24 |
| Store | 70 | 192.168.7.0/24 |
| Reception | 80 | 192.168.8.0/24 |

---

## 🔐 Security Implementation

- **SSH** enabled on all routers for encrypted remote access  
- **Port Security** applied in IT department:
  - Sticky MAC
  - Maximum one device
  - Violation mode: shutdown  

These measures protect critical network infrastructure.

---

## 🧪 Testing & Verification

The following tests were successfully performed:
- Inter-VLAN connectivity
- Inter-floor communication
- DHCP IP assignment
- OSPF neighbor formation
- SSH remote login
- Port security violation testing

---

## 🔧 How to Use This Project

1. Download the `Hotel_Management_Network.pkt` file  
2. Open it using **Cisco Packet Tracer**  
3. Test connectivity using:
   - `ping`
   - `show ip route`
   - `show ip ospf neighbor`
   - `ssh`

---

## 📁 Repository Structure
Hotel-Management-Network/
│
├── README.md
├── Hotel_Management_Network.pkt
├── config/
│ ├── F1-Router.txt
│ ├── F2-Router.txt
│ ├── F3-Router.txt
│ ├── F1-Switch.txt
│ ├── F2-Switch.txt
│ └── F3-Switch.txt
│
├── notes/
│ ├── Network_Overview.md
│ ├── VLAN_and_IP_Plan.md
│ ├── OSPF_and_DHCP.md
│ └── Security_SSH_PortSecurity.md
│
└── images/
└── topology.png


---

## 👨‍💻 Author

**Anup Kumar Singh**  
BCA Student | Network Design & Simulation  

This project was developed as part of hands-on practice to demonstrate real-world enterprise network design, configuration, and security concepts.

---

## ⭐ If You Like This Project
Give it a ⭐ on GitHub and feel free to fork or reuse it for learning purposes.



