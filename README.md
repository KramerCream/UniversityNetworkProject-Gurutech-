# University Campus System Network Design

## Project Overview

This project simulates a medium-sized hierarchical network using Cisco Packet Tracer. The topology includes multiple departments and VLANs, inter-VLAN routing, dynamic IP assignment, and secure remote access configurations. The aim is to build a scalable and secure network infrastructure suitable for an enterprise environment.

---

## 📋 Project Objectives

- Create a hierarchical network topology using Cisco Packet Tracer.
- Connect networking devices with appropriate cabling.
- Implement VLANs for logical segmentation.
- Perform subnetting and IP addressing.
- Configure Inter-VLAN Routing (Router-on-a-Stick).
- Set up DHCP pools on the router for dynamic IP allocation.
- Enable SSH for secure remote access to network devices.
- Use RIPv2 as the dynamic routing protocol.
- Apply Switchport Security on access ports.
- Configure host devices.
- Test and verify full network communication.

---

## VLAN and Subnet Configuration Table

| Department     | VLAN ID | Subnet               | Default Gateway   |
|----------------|---------|----------------------|-------------------|
| Management     | 10      | 192.168.1.0/24       | 192.168.1.1       |
| HR             | 20      | 192.168.2.0/24       | 192.168.2.1       |
| Finance        | 30      | 192.168.3.0/24       | 192.168.3.1       |
| FoB            | 40      | 192.168.4.0/24       | 192.168.4.1       |
| ComputerSF     | 50      | 192.168.5.0/24       | 192.168.5.1       |
| ArtDesign      | 60      | 192.168.6.0/24       | 192.168.6.1       |
| StudentLab     | 70      | 192.168.7.0/24       | 192.168.7.1       |
| ITDepartment   | 80      | 192.168.8.0/24       | 192.168.8.1       |
| Staff          | 90      | 192.168.9.0/24       | 192.168.9.1       |
| Student        | 100     | 192.168.10.0/24      | 192.168.10.1      |

> All DHCP pools are configured on the router. Each VLAN is assigned to its corresponding subnet and gateway.

---

Here is the visual representation of the topology: 
<img width="2681" height="1094" alt="UniversityCampusNetworkProject" src="https://github.com/user-attachments/assets/ab3a66dd-5066-48b7-b99f-b8bb117fec82" />

---


## Routing Protocol

- **RIPv2** is used for dynamic routing between VLAN interfaces.

---

## Security Features

- **SSH** configured for secure remote access on the router.
- **Switchport Security** applied on access ports to prevent unauthorized device access.

---

## Notes

- Host devices are assigned IPs dynamically using the router's DHCP pools.
- VLAN interfaces (SVIs) are created for each department.
- All devices are verified for successful communication using `ping`, `traceroute`, and `SSH`.

---

## 📁 Included Files

- `https://github.com/KramerCream/UniversityNetworkProject-Gurutech-/blob/main/University%20Campus%20Project.pkt` (Packet Tracer file)

---


