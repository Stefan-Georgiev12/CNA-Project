## CNA-Project

This project is a simulation of a multi-area OSPF network using Cisco Packet Tracer. It includes routing, DHCP, DNS, and testing of end-to-end connectivity across different subnets.

 Project Contents

- `Project.pka`: Main Cisco Packet Tracer simulation.
- `Project.pkz`: Compressed or backup version of the project.

 Network Topology

The topology is built using:
- **5 Routers**: connected across Area 0 and Area 1.
- **Multiple Switches**: used for LAN device access.
- **2 Laptops**: receiving dynamic IP addresses.
- **DHCP Server**: assigns IPs in LAN subnet `10.1.2.0/24`.
- **DNS Server**: used for name resolution in `192.168.1.0/24`.
- **WWW Server**: located in `192.168.2.0/24`, simulates external web access.

OSPF Configuration

- **Area 0** (Backbone): Includes subnets `10.11.11.0/24` and `10.1.2.0/24`.
- **Area 1**: Includes `10.12.12.0/28` and connects to the WWW server.
- **OSPF Neighbors** are configured between all routers for dynamic routing.

 Services Used

- **DHCP**: Automatically assigns IPs to laptops.
- **DNS**: Allows hostname resolution.
- **OSPF**: Enables dynamic routing between areas.
- **Ping/PC Tests**: Used to verify connectivity and routing.
