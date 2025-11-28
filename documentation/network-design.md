# Network Design Specification

## IP Addressing Scheme
- Router LAN Interface: 192.168.0.1/24
- Subnet Mask: 255.255.255.0
- DHCP Pool: Automatic (192.168.0.x range)
- DNS Server: Not configured (0.0.0.0)

## Device IP Assignments
- Router: 192.168.0.1
- PC0: 192.168.0.104 (DHCP)
- PC1: 192.168.0.105 (DHCP) 
- Smartphone: 192.168.0.103 (DHCP)
- Laptop: DHCP assigned

## Wireless Configuration
- SSID: MyHomeWifi
- Security Protocol: WPA2-Personal
- Passphrase: HomeNetwork123
- Band: 2.4GHz Mixed Mode
- Channel: Auto

## Physical Connections
- Cloud0 ↔ Wireless Router (Internet Port)
- Wireless Router (LAN Port) ↔ Switch0
- Switch0 ↔ PC0 (FastEthernet)
- Switch0 ↔ PC1 (FastEthernet)
- Laptop0 ↔ Wireless (WiFi)
- Smartphone0 ↔ Wireless (WiFi)

## Verified Connectivity
- All wired devices can ping the router (192.168.0.1)
- Wired devices can communicate with each other
- Wireless devices successfully associated with SSID
- End-to-end network functionality confirmed