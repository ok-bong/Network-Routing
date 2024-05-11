# Network Routing Scenarios

## Overview
This repository contains 6 scenarios demonstrating the configuration of Cisco routers and switches for a fully functional internal corporate network. Each scenario shows the implementation of dynamic routing protocols - RIP, EIGRP, and OSPF. Additionally, inter-VLAN routing is configured, and each scenario includes a simulation of Internet through an ISP router (using loopback interfaces).

VLANs, IP address design, and VLSM calculations are documented in each scenario's Packet Tracer file.


## General Configuration
- **Gateway Router**: The gateway router of the internal network has a default route pointing to the ISP, while the ISP router has a single static route directing all traffic to the corporate network's gateway router.
- **Internal Network Setup**: All internal routers are connected to switches using trunk connections for inter-VLAN routing.
- **Password**: The password for switches and routers in all scenarios is **cisco**.

## Scenarios

### Scenario 1: RIPv2 and Wireless Router Configurations
- Demonstrates the configuration of RIPv2 routing protocol.
- Includes configurations for a wireless router to extend network connectivity.
- Conducted tests to confirm full connectivity between devices.

### Scenario 2: RIPv2 and ACL (Extended)
- Uses RIPv2 for dynamic routing.
- Implements Access Control Lists (ACLs) to control traffic flow.
- Comprehensive testing ensures proper connectivity.

### Scenario 3: EIGRP, ACL (Extended & Standard)
- Configuration of EIGRP as the dynamic routing protocol.
- ACLs (extended & standard) are configured for traffic control.
- Extensive testing validates network connectivity.

### Scenario 4: OSPF, ACL (Extended & Standard)
- OSPF is configured as the dynamic routing protocol.
- ACLs (extended & standard) are employed for security and traffic management.
- Thorough testing ensures seamless communication.

### Scenario 5: OSPF, ACL (Extended & Standard), DHCP, NAT
- OSPF is implemented for dynamic routing.
- Includes ACLs (extended & standard) for security.
- DHCP and NAT services are configured for address management and internet access.
- Rigorous testing validates network functionality.

### Scenario 6: OSPF, DHCP, NAT, ACL (Extended & Standard), PPP and CHAP
- OSPF is configured as the dynamic routing protocol.
- DHCP and NAT services are set up for address allocation and internet connectivity.
- Includes ACLs (extended & standard) for traffic control.
- Uses PPP and CHAP for secure communication.
- Thorough testing confirms network integrity.

## Usage
1. Open the respective Packet Tracer file for each scenario.
2. Review the configurations and network topology.
3. Conduct tests as specified in the scenario to verify connectivity.
4. Explore additional features and technologies implemented in each scenario.

