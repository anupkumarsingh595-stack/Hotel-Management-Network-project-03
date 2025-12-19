# Network Security: SSH and Port Security

## SSH (Secure Shell)

SSH is configured on all routers to allow secure remote management.

### SSH Features
- Encrypted communication
- Username and password authentication
- Prevents insecure Telnet access

### Usage
- SSH access is tested from the IT department Test-PC.
- Only authorized users can log in to routers.

---

## Port Security

Port security is implemented on the IT department switch.

### Configuration Details
- Applied on FastEthernet0/1
- Maximum one device allowed
- Sticky MAC address enabled
- Violation mode set to shutdown

### Purpose
The IT department is the most sensitive area of the network.
Port security prevents unauthorized devices from connecting.
