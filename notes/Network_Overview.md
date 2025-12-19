# Network Overview

This project represents a three-floor hotel management network designed using Cisco Packet Tracer.

The main objective of the network is to provide reliable, secure, and scalable communication between all hotel departments while maintaining proper separation using VLANs.

## Network Structure
- The hotel has three floors.
- Each floor has one switch and one router.
- Routers are interconnected using serial WAN links.
- All routing is handled dynamically using OSPF.

## Design Approach
- VLANs are used to separate departments.
- Router-on-a-Stick is used for inter-VLAN routing.
- OSPF Area 0 is used for simplicity and scalability.
- DHCP is used for automatic IP address allocation.
- SSH is implemented for secure remote management.

This design follows real-world enterprise networking practices.
