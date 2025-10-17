# packet-tracer-basic-switch-config-physical-mode

A hands-on Cisco Packet Tracer lab for basic switch configuration. Covers console setup, hostnames, passwords, VLANs, and SVI management. Practice IP addressing (IPv4/IPv6), connectivity testing, and remote access via Telnet. Essential for CCNA networking fundamentals.

# Topology
![Topology](packet-tracer-physical-mode-configuration/topology.jpg)  

# Addressing Table

| Device | Interface | IP Address / Prefix | Default Gateway | 
| :---   |  :---:    |       :---:         |  :---:          |
| S1     |  VLAN 99  | 192.168.1.2 /24     | 192.168.1.1     |
| S1     |  VLAN 99  | 2001:DB8:ACAD:1::2 /64 | fe80:1::1    |
| S1     |  VLAN 99  | FE80::2             |                 |
| PC-A   |  NIC      | 192.168.1.10 /24    |192.168.1.1      |
| PC-B   |  NIC      | 22001:DB8:ACAD:1::10 /64 | fe80:1::1  |

# Lab Objectives

# Part 1: Cable the Network and Verify Default Switch Configuration

- Establish physical connections

- Examine default switch settings

- Verify interface properties and VLAN information

# Part 2: Configure Basic Network Device Settings

- Set device hostname and passwords

- Configure management VLAN

- Implement security features

- Assign IP addresses

# Part 3: Verify and Test Network Connectivity

- Test end-to-end connectivity

- Configure remote management

- Validate switch deployment

- Key Learning Outcomes

# Switch Configuration Skills

- Initial Console Access: Learn why console connection is required for initial configuration

- Basic Switch Settings: Configure hostnames, passwords, and MOTD banners

- VLAN Management: Create and configure management VLAN (VLAN 99)

- IP Addressing: Assign IPv4 and IPv6 addresses to Switch Virtual Interface (SVI)

- Remote Access: Enable Telnet for remote switch management

# Security Implementation

- Password Security: Configure enable secret, console, and vty passwords

- VLAN Best Practices: Move management from default VLAN 1 to VLAN 99

- Access Control: Restrict console and vty line access

# Verification and Testing

- Connectivity Testing: Use ping to verify network connectivity

- Configuration Verification: Validate settings using show commands

- Remote Management: Test Telnet access to the switch




































