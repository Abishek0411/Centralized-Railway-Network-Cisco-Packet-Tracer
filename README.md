# Centralized Railway Ticketing Network

## Overview
This project demonstrates the design and simulation of a **Centralized Railway Ticketing Network** using Cisco Packet Tracer. The network supports real-time ticketing, administrative operations, and secure communication across multiple railway stations, regional offices, and public interfaces (kiosks and mobile apps). The design emphasizes scalability, reliability, and security.

## Key Features
- **Centralized Server Infrastructure**: Includes ticketing, database, and backup servers located in the data center.
- **Three-Layer Hierarchical Model**:
  - **Core Layer**: Centralized routing and server connectivity.
  - **Distribution Layer**: Regional offices with Layer 3 switches for inter-VLAN routing.
  - **Access Layer**: Station-level access switches for ticket counters and administrative PCs.
- **VLAN Segmentation**: Segregates traffic for ticketing, administration, customer service, and public access.
- **Dynamic and Static Routing**:
  - OSPF for internal dynamic routing.
  - Static routes for external connections to cloud-based services.
- **Robust Security**: Implements port security, ACLs, and secure access for public-facing interfaces.

## Project Objectives
- Create a centralized ticketing system accessible from all connected railway stations.
- Design a scalable IP addressing scheme to manage traffic efficiently.
- Implement VLANs for better traffic isolation and security.
- Configure inter-VLAN routing and dynamic routing protocols for seamless communication.
- Test and validate connectivity, redundancy, and security measures.

## Network Design
- **Core Layer**:
  - High-speed core routers connecting to centralized servers and ISPs.
  - Secure external interfaces for kiosks and mobile apps.
- **Distribution Layer**:
  - Layer 3 switches at regional offices for inter-VLAN routing and local traffic management.
- **Access Layer**:
  - Layer 2 switches at ticket counters and service desks.
- **Public Access**:
  - Secure external connections for customer kiosks and mobile apps via NAT and ACLs.

## Technologies Used
- Cisco Packet Tracer (Simulation and Design)
- OSPF (Dynamic Routing Protocol)
- VLANs (Virtual Local Area Networks)
- DHCP (Dynamic IP Address Allocation)
- ACLs (Access Control Lists) for security
- NAT (Network Address Translation) for public access interfaces

## File Contents
- **Project Design**: `.pkt` file containing the network topology designed in Cisco Packet Tracer.
- **Documentation**: Includes a detailed report on the network design, IP addressing scheme, and testing results.
- **README.md**: This file.

## How to Run the Simulation
1. Open the `.pkt` file in Cisco Packet Tracer.
2. Review the network topology and configurations.
3. Test connectivity between ticket counters, regional offices, and the centralized servers.
4. Simulate external access through kiosks or mobile apps to validate public access routing.
5. Verify redundancy by disabling links or devices to observe failover functionality.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to modify and use it for educational purposes.
