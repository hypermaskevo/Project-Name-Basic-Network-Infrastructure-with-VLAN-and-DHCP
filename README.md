Project Name: Basic Network Infrastructure with VLAN and DHCP
Objective
The goal of this project is to build a basic network infrastructure using Cisco Packet Tracer. The project includes configuring VLANs, DHCP, and ensuring connectivity between devices. The final configuration will be documented and uploaded to GitHub.

Estimated Time
Approximately 3-4 hours

Project Scope
Setting up the network topology in Cisco Packet Tracer
Configuring the router with IP addresses and DHCP
Configuring switches with VLANs and Trunk connections
Testing the network to ensure connectivity
Uploading the configuration files to GitHub
Part 1: Network Topology Setup
Devices Required
1 Cisco 2911 Router
2 Cisco 2960 Switches
4 PCs
Connections
Router (GigabitEthernet0/0) → (FastEthernet0/1) Switch 1
Router (GigabitEthernet0/1) → (FastEthernet0/1) Switch 2
Switch 1 and Switch 2 connected via Trunk (GigabitEthernet0/2)
Two PCs connected to each switch on FastEthernet0/2 and FastEthernet0/3
Part 2: Router Configuration
The router will be configured with IP addresses and DHCP settings to assign IP addresses dynamically to clients.

Router Configuration Commands
![1](https://github.com/user-attachments/assets/df62494b-0d8c-4b3d-869f-2393742494c4)

Part 3: Switch Configuration
The switches will be configured to support VLANs and Trunking.
Switch 1 Configuration Commands
![2](https://github.com/user-attachments/assets/d6dfba48-2dad-4232-99e8-61aa8bcc0c68)

Switch 2 Configuration Commands
![3](https://github.com/user-attachments/assets/01459b50-83a1-4ecc-8ff8-55e4ab1a76b8)

Part 4: Network Testing
The network will be tested to verify that PCs are assigned IP addresses via DHCP and that VLAN communication works as expected.

Verify DHCP on PCs
On PC1 (VLAN 10), run:
![4](https://github.com/user-attachments/assets/8242cffd-b30a-4eae-8d13-38cc348e91e5)

On PC3 (VLAN 20), run:
![6](https://github.com/user-attachments/assets/efbba311-a1cb-45dc-aa23-0190fc45276f)



Ping Between Devices

![5](https://github.com/user-attachments/assets/6c86c115-349e-4778-9208-a71447d7d47d)

Ping Router from PCs
![7](https://github.com/user-attachments/assets/bcab3131-7b88-4c70-907f-16cdb4e32569)



