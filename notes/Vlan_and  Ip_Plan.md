# VLAN and IP Addressing Plan

Each department in the hotel is assigned a unique VLAN and IP network.
This improves security, reduces broadcast traffic, and makes the network easier to manage.

## VLAN Assignment

### 1st Floor
- VLAN 80 – Reception – 192.168.8.0/24
- VLAN 70 – Store – 192.168.7.0/24
- VLAN 60 – Logistics – 192.168.6.0/24

### 2nd Floor
- VLAN 50 – Finance – 192.168.5.0/24
- VLAN 40 – HR – 192.168.4.0/24
- VLAN 30 – Sales – 192.168.3.0/24

### 3rd Floor
- VLAN 20 – Admin – 192.168.2.0/24
- VLAN 10 – IT – 192.168.1.0/24

## Default Gateway Rule
For each VLAN, the default gateway is the router sub-interface ending with `.1`.

Example:
- VLAN 10 → 192.168.1.1
- VLAN 80 → 192.168.8.1
