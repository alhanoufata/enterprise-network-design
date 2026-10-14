# enterprise-network-design
# Multi-Site Enterprise Network Design with Cisco Packet Tracer

## Project Overview

This project demonstrates the design and configuration of a segmented enterprise network using Cisco Packet Tracer. It includes multiple VLANs, inter-VLAN routing, OSPF, centralized network services, and access control between selected departments.

## Objectives

- Segment the network into departmental VLANs.
- Enable communication between permitted network segments.
- Configure OSPF for dynamic routing.
- Provide DHCP, DNS, and HTTP services.
- Apply ACLs to restrict communication between selected departments, including HR and Finance.
- Explore centralized NAT configuration.

## Technologies

- Cisco Packet Tracer
- VLANs and 802.1Q trunking
- Inter-VLAN Routing
- OSPF
- DHCP and DNS
- HTTP
- Access Control Lists (ACLs)
- Network Address Translation (NAT)

## Network Design

The topology includes a main site, a branch network, departmental VLANs, routers, switches, and servers.

The IP addressing plan and VLAN assignments are documented in the `documentation/` directory.

## Implementation and Testing

The project includes routing configuration, VLAN segmentation, network services, and ACL-based traffic restrictions.

Connectivity and service tests are documented using screenshots and command outputs.

## NAT Status

Centralized NAT configuration was attempted but has not yet been fully validated. NAT is therefore not presented as a successfully completed feature.

## Project Files

- `packet-tracer/`: Packet Tracer project file.
- `screenshots/`: Evidence of network configuration and testing.
- `configurations/`: Device configuration excerpts.
- `documentation/`: Addressing plan, design notes, and test results.

## Learning Outcomes

This project provided practical experience with network segmentation, routing, network services, access control, troubleshooting, and technical documentation.
