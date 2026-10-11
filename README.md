# Cisco Packet Tracer — Home Network Lab

## Project Overview
This project simulates a home network using Cisco Packet Tracer. It connects a wired PC and a wireless laptop through a WRT300N wireless router.

## Objectives
- Configure a wireless home network.
- Understand IPv4 addressing and subnet masks.
- Use DHCP to assign IP addresses automatically.
- Configure Wi-Fi security.
- Test connectivity using the `ping` command.

## Network Topology
![Home Network Topology](topology.png)

## Devices Used
- WRT300N wireless router
- PC0 connected through Ethernet
- Laptop0 connected through Wi-Fi

## IP Addressing Plan

| Device | Connection | IP Address | Subnet Mask |
|---|---|---|---|
| Router | LAN | 192.168.0.1 | 255.255.255.0 |
| Laptop0 | Wireless | 192.168.0.101 | 255.255.255.0 |
| PC0 | Ethernet | 192.168.0.102 | 255.255.255.0 |

The devices obtained their IP addresses through DHCP during the lab.

## Configuration and Testing
- Configured the Wi-Fi SSID and WPA2 security.
- Enabled DHCP on the wireless router.
- Connected the laptop wirelessly and the PC through Ethernet.
- Verified IP configuration using `ipconfig`.
- Tested connectivity to the router and between the laptop and PC using `ping`.

## DHCP and IP Configuration
![DHCP and IP Configuration](dhcp-ipconfig.png)

## Connectivity Test
![Successful Ping Test](ping-success.png)

## Key Learning Outcomes
- Home networking fundamentals
- Wired Ethernet and wireless connectivity
- IPv4 addressing and subnet masks
- DHCP and default gateway concepts
- Basic connectivity testing and troubleshooting

## Tools Used
- Cisco Packet Tracer
- IPv4
- DHCP
- ICMP ping

## Project Scope
This lab demonstrates local network communication. An ISP/WAN connection and Internet access were not configured.

## Future Improvements
- Configure multiple subnets.
- Add a router and practise inter-network routing.
- Troubleshoot incorrect IP addresses and subnet masks.
- Explore DNS and simulated Internet connectivity.
# packet-tracer-home-network
Cisco Packet Tracer home network lab using Wi-Fi, DHCP, IPv4 and connectivity testing. 
