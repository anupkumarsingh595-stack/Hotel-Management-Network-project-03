# OSPF and DHCP Configuration

## OSPF (Open Shortest Path First)

OSPF is used as the dynamic routing protocol in this network.

### Why OSPF?
- Automatically shares routes between routers
- Scales well for enterprise networks
- Eliminates the need for static routes

### OSPF Design
- Process ID: 1
- Area: 0
- Advertises all VLAN networks and WAN links

Result:
All devices across all floors can communicate with each other.

---

## DHCP (Dynamic Host Configuration Protocol)

DHCP is configured on all routers.

### DHCP Purpose
- Automatically assigns IP addresses
- Reduces configuration errors
- Saves time during deployment

### DHCP Design
- One DHCP pool per VLAN
- Default gateway set to router sub-interface
- IP exclusions applied for gateway and reserved addresses

All end devices (PCs, laptops, phones, printers) use DHCP.
