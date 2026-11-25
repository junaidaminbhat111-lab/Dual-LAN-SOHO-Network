## Project Overview
A completed Dual-LAN Small Office/Home Office (SOHO) networking project demonstrating router configuration, two LAN networks, IP addressing and connectivity testing.

## Topology
- Cisco 2911-style router
- 2 switches
- 4 PCs
- Simulated ISP connection
- 2 LAN networks

## IP Addressing
- LAN 1: 192.168.1.1/24
- LAN 2: 192.168.2.1/24
- Router WAN: 10.0.0.2
- ISP gateway: 10.0.0.1

## Explanation of each command
- Command : configure terminal
- Enters global configuration mode.
- Allows you to change router settings.


- Command : interface g0/0
- Selects GigabitEthernet0/0.
- You are now configuring that interface.


- Command : ip nat inside
- Marks GigabitEthernet0/0 as an internal NAT interface.
- Usually connected to a LAN or internal network.


- Command : interface g0/2
- Selects GigabitEthernet0/2.

- Command : ip nat inside
- Marks GigabitEthernet0/2 as another internal NAT interface.

- Command : interface g0/1
- Selects GigabitEthernet0/1.

- Command : ip nat outside
- Marks GigabitEthernet0/1 as the external NAT interface.
- Usually connected toward the ISP or external network.

- Command : end
- Exits configuration mode and returns to privileged mode.

## Skills Demonstrated
- Router interface configuration
- IP addressing and subnetting
- Static routing
- Network connectivity testing
- Cisco IOS commands
- LAN troubleshooting

## Testing
Ping tests were performed successfully across the network.

## Project Status
Completed.
<img width="1171" height="628" alt="projectsss" src="https://github.com/user-attachments/assets/cbf21ae7-d232-4f35-ae30-25386af61644" />

## Author
Junaid Amin Bhat
