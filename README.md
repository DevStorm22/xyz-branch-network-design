# XYZ Company — Branch Network Design

A hands-on enterprise networking project designed and simulated using **Cisco Packet Tracer**. The project focuses on implementing a small, independent branch network for XYZ Company with departmental VLANs, wireless connectivity, automatic IPv4 addressing, and interdepartmental communication.

## Project Overview

XYZ Company is a growing food trading business planning to establish a new branch near Bonalbo, Eastern Australia. The branch network must operate independently of the company's headquarters while providing secure departmental segmentation and communication between users.

This project implements the proposed branch network using Cisco networking devices and the private IPv4 address space `192.168.1.0/24` as the starting network allocation.

## Objectives

- Design a branch network using Cisco router and switch devices.
- Create separate VLANs for the three departments.
- Provide wireless network access for departmental users.
- Configure DHCP to assign IPv4 addresses automatically.
- Enable communication between devices across all departments.
- Implement inter-VLAN routing.
- Verify addressing, connectivity, and network functionality.

## Network Requirements

| Requirement | Description |
|---|---|
| Organization | XYZ Company — Branch Office |
| Network devices | One Cisco router and one Cisco switch |
| Departments | Admin/IT, Finance/HR, Customer Service/Reception |
| Network segmentation | Separate VLAN for each department |
| Wireless access | Required for all departments |
| IP addressing | Automatic IPv4 assignment using DHCP |
| Interdepartmental communication | Required |
| Base network | `192.168.1.0/24` |
| Simulation tool | Cisco Packet Tracer |

## Network Topology

*Add a screenshot of the completed Packet Tracer topology here.*

The proposed topology uses a Cisco router and a managed Cisco switch to connect the departmental networks. Wireless access points or suitable wireless networking devices provide connectivity for wireless users.

The router provides inter-VLAN routing, while the switch separates departmental traffic using VLANs. DHCP provides automatic IPv4 configuration to client devices.

## VLAN and IP Addressing Plan

The base network `192.168.1.0/24` will be subnetted according to the requirements of each department.

| Department | VLAN | Network Address | Default Gateway |
|---|---:|---|---|
| Admin/IT | 10 | To be configured | To be configured |
| Finance/HR | 20 | To be configured | To be configured |
| Customer Service/Reception | 30 | To be configured | To be configured |

*Update the network addresses, subnet masks, and gateways according to the final subnetting plan.*

## Technologies and Tools

- Cisco Packet Tracer
- Cisco router and managed switch
- VLANs and 802.1Q trunking
- Inter-VLAN routing
- DHCP and IPv4 addressing
- Wireless networking
- Network connectivity testing using `ping`

## Project File

- `xyz-branch-network.pkt` — Editable Cisco Packet Tracer network simulation.

## Demonstration Video

*Add a link to the project demonstration video here.*

The demonstration will showcase the network topology, VLAN configuration, wireless connectivity, DHCP address allocation, routing configuration, and connectivity tests between departments.

## Testing and Verification

The following checks will be performed:

- Verify VLAN creation and switch port assignments.
- Verify trunk configuration and router subinterfaces.
- Confirm that client devices receive IPv4 addresses automatically through DHCP.
- Verify wireless client connectivity.
- Test communication between devices within the same department.
- Test interdepartmental communication across all three VLANs.

Record the actual results after testing the completed simulation.

## Expected Outcome

The completed branch network should provide separate VLANs for all three departments, wireless access for users, automatic IPv4 addressing through DHCP, and communication between devices across departmental networks.

The branch network is designed as an independent network environment, separate from the headquarters network.

## Learning Outcomes

This project provides practical experience in enterprise network design, VLAN segmentation, wireless networking, DHCP configuration, IPv4 subnetting, inter-VLAN routing, and network verification.

## Disclaimer

This project is intended for educational purposes and networking skills practice in a simulated environment.