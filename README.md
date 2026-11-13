# Project 01 – VLANs & Inter-VLAN Routing

## Project Overview
Design and implementation of a small enterprise network using Cisco Packet Tracer.

## Objectives
- Configure VLAN 10 (Sales).
- Configure VLAN 20 (IT).
- Configure Access and Trunk ports.
- Implement Router-on-a-Stick.
- Configure DHCP for both VLANs.
- Verify inter-VLAN connectivity.

## Network Topology
![Network Topology](Screenshots/01_topology.svg)

## IP Addressing

| VLAN | Department | Network | Gateway |
|---|---|---|---|
| 10 | Sales | 192.168.10.0/24 | 192.168.10.1 |
| 20 | IT | 192.168.20.0/24 | 192.168.20.1 |

## Technologies
- Cisco Packet Tracer
- VLAN
- 802.1Q Trunking
- Router-on-a-Stick
- DHCP
- IPv4

## Verification
- VLAN configuration verified.
- Trunk link verified.
- DHCP address assignment tested.
- Inter-VLAN connectivity verified using ICMP Ping.

## Files
- Packet Tracer simulation: `Packet-Tracer/`
- Device configurations: `Configurations/`
- Test screenshots: `Screenshots/`

## Disclaimer
This project is a personal educational lab developed in Cisco Packet Tracer. It is not a production deployment.
