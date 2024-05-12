# Network Routing Scenarios

## Overview
This repository contains 6 scenarios demonstrating the configuration of Cisco routers and switches for a fully functional internal corporate network using dynamic routing protocols (RIP, EIGRP, OSPF), interVLAN routing, and other advanced networking concepts using Cisco Packet Tracer. Each scenario includes a simulation of an ISP router using a loopback interface to simulate network connectivity to the internet.

VLANs, IP address design, and VLSM calculations are documented in each scenario's Packet Tracer file.

Each folder corresponding to each scenario will contain a .pkt file, configuration of each router/switch, and README file detailing each scenario's requirements.

## General Configurations

- **Gateway Configuration**: The gateway router of the internal network will have a default route pointing to the ISP, and the ISP will have a single static route directing all traffic to the corporate network to the Corporate Gateway router.
- **Internal Network Topology**: All internal routers are connected to switches using trunk connections for interVLAN routing.
- **Switch Port Security**: Implement port security settings on switch access ports. Configure port security with mac address sticky, maximum 4 addresses, and violation protect mode to enhance network security.
- **Switch Configuration**: If applicable, configure the switch with an enable password of "cisco". Define the necessary VLANs, assign a management interface to VLAN1, set up a default gateway, and enable telnet access with the password "cisco" to facilitate remote management of the switch.
- **Testing Connectivity**: All necessary tests have been conducted to confirm that PCs have full connectivity between each other and that all devices can communicate properly with other directly connected devices.

## Scenarios Overview

### Scenario 1: RIPv2 and Wireless Router Configuration

Configuring RIPv2 for dynamic routing and setting up a wireless router for network access.

### Scenario 2: RIPv2 and ACL (Extended)

RIPv2 is configured alongside extended ACLs for network security and access control.

### Scenario 3: EIGRP, ACL (Extended & Standard)

EIGRP is implemented as the dynamic routing protocol, and both extended and standard ACLs are used for network security.

### Scenario 4: OSPF, ACL (Extended & Standard)

OSPF is implemented as the dynamic routing protocol, with extended and standard ACLs for network security.

### Scenario 5: OSPF, ACL (Extended & Standard), DHCP, NAT

OSPF is configured for dynamic routing, DHCP and NAT are implemented alongside ACLs for network security.

### Scenario 6: OSPF, DHCP, NAT, ACL (Extended & Standard), PPP and CHAP

OSPF for dynamic routing, DHCP and NAT for address management, ACLs for network security, and PPP with CHAP for secure authentication.