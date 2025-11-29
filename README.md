# 🏠 Home Network Simulation in Cisco Packet Tracer

A complete home network setup demonstrating networking fundamentals using only GUI configuration.

## 📋 Project Overview
This project simulates a typical home network environment with both wired and wireless connectivity, configured entirely through Cisco Packet Tracer's graphical interface without CLI commands.

## 🌐 Network Topology
![Network Diagram](images/network-topology.png)

## 🛠️ Devices Configuration
| Device | Role | Connection Type | IP Address |
|--------|------|-----------------|------------|
| WRT300N | Wireless Router | Internet + WiFi | 192.168.0.1 |
| 2960-24TT | Switch | Wired Distribution | N/A |
| PC-PT (PC0) | Desktop Computer | Wired Ethernet | DHCP |
| PC-PT (PC1) | Desktop Computer | Wired Ethernet | DHCP |
| Laptop-PT | Mobile Device | Wireless | DHCP |
| SMARTPHONE-PT | Mobile Device | Wireless | DHCP |

## 🔧 Features Implemented
- ✅ Internet connectivity via Cloud simulation
- ✅ Wireless network with WPA2 security (SSID: MyHomeWifi)
- ✅ Switch-based wired network
- ✅ DHCP automatic IP assignment
- ✅ Inter-device connectivity verified with ping tests

## 🚀 Getting Started
1. Download `home-network.pkt` from the `packet-tracer-files/` folder
2. Open in Cisco Packet Tracer 8.x or newer
3. All configurations are pre-set via GUI

## 📊 Connectivity Verification
All devices successfully communicate with each other and the router:

**Ping Test Results:**
- PC0 → Router (192.168.0.1): ✅ 0% packet loss
- PC0 → PC1 (192.168.0.105): ✅ 0% packet loss  
- PC1 → Router (192.168.0.1): ✅ 0% packet loss
- PC1 → PC0 (192.168.0.104): ✅ 0% packet loss

![Ping Test PC0](images/connectivity-tests/ping-test-fromPC0.png)
![Ping Test PC1](images/connectivity-tests/ping-test-fromPC1.png)

