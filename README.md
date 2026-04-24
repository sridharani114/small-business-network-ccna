# small-business-network-ccna
c# Small Business Network — CCNA Project

## Overview
Designed and implemented a multi-department 
enterprise network in Cisco Packet Tracer.

## Topology
![Topology](screenshots/topology.png)

## Devices Used
- Cisco 3650 Multilayer Switch (Layer 3)
- Cisco 2911 Router
- 2x Cisco 2960 Access Switches
- 4x PCs
- 1x Server

## VLANs
| VLAN | Department | Subnet |
|------|-----------|--------|
| 10   | HR        | 192.168.10.0/24 |
| 20   | IT        | 192.168.20.0/24 |
| 30   | Sales     | 192.168.30.0/24 |
| 40   | Guest     | 192.168.40.0/24 |

## Features Implemented
- Inter-VLAN Routing (Layer 3 Switch)
- DHCP Server
- ACL (Guest blocked from HR and IT)
- Static Routing
- Trunk Ports
- Port Security

## How to Open
1. Install Cisco Packet Tracer (free via NetAcad)
2. Open packet-tracer/small-business-network.pkt

## Test Results
- All PCs get IP from DHCP Server ✅
- Inter-VLAN routing working ✅
- Guest VLAN blocked from HR and IT ✅
