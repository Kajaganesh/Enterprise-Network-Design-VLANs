# Enterprise-Network-Design-VLANs
Cisco Packet Tracer project: Multi-VLAN enterprise network with centralized servers and inter-VLAN routing.
# Enterprise Network Design with VLANs and Inter-VLAN Routing

## Project Overview
This project simulates a real-world enterprise network using Cisco Packet Tracer. It demonstrates:

- Network segmentation with VLANs
- Inter-VLAN routing using Router-on-a-Stick
- Centralized services (DHCP, DNS, HTTP, FTP)
- Network troubleshooting and verification

## Network Architecture
**Departments and VLANs:**

| VLAN | Department | Subnet           | Gateway         |
|------|------------|-----------------|----------------|
| 10   | HR         | 192.168.10.0/24 | 192.168.10.1   |
| 20   | IT         | 192.168.20.0/24 | 192.168.20.1   |
| 30   | Sales      | 192.168.30.0/24 | 192.168.30.1   |

**Devices Used:**

- Cisco 2901 Router
- Cisco 2960 Layer-2 Switches
- PCs, Printers
- Centralized Servers (DHCP/DNS, HTTP, FTP)

## Key Features Implemented
- VLAN configuration and segmentation
- Router-on-a-Stick with 802.1Q trunking
- Centralized server infrastructure
- Inter-VLAN communication
- Troubleshooting with `ping`, `show ip interface brief`, `show vlan brief`, `show interfaces trunk`

## Screenshots
![VLAN Topology](Diagrams/VLAN-Topology.png)

## How to Use
1. Open `EnterpriseNetwork.pkt` in Cisco Packet Tracer.
2. Verify connectivity using pings between VLANs.
3. Check centralized services from IT VLAN.

## Learning Outcomes
- Practical understanding of enterprise network design
- Hands-on experience with VLANs, inter-VLAN routing, and server deployment
- Troubleshooting and verification using Cisco IOS
