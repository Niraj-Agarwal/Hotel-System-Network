# Welcome to the Vic Modern Hotel Network Design project!
This project focuses on creating a comprehensive network solution for a modern hotel with multiple departments spread across three floors. The network is designed to ensure secure, efficient, and seamless communication between all devices.

## Project Overview 
The Vic Modern Hotel has three floors, each hosting different departments:

- **1st Floor**: Reception, Store, Logistics
- **2nd Floor**: Finance, HR, Sales/Marketing
- **3rd Floor**: IT, Admin
### Key Considerations
- **Three routers** connect each floor, all located in the server room within the IT department.
- **Serial DCE** cables are used to connect the routers.
- **Subnetting** is implemented between routers with networks 10.10.10.0/30, 10.10.10.4/30, and 10.10.10.8/30.
- Each floor has its own **switch** to manage wired connections.
- **Wi-Fi networks** are set up on each floor to support laptops and mobile devices.
- **Printers** are provided for each department, with each department in its own VLAN:
    - **1st Floor**: VLAN 80 (Reception), VLAN 70 (Store), VLAN 60 (Logistics)
    - **2nd Floor**: VLAN 50 (Finance), VLAN 40 (HR), VLAN 30 (Sales)
    - **3rd Floor**: VLAN 20 (Admin), VLAN 10 (IT)
### Technologies Implemented
- **Network Topology Design**: Created using Cisco Packet Tracer, following a hierarchical network design.
- **Correct Cabling**: Connected networking devices with appropriate cabling.
- **VLAN Configuration**: Each department is assigned to a specific VLAN.
- **Subnetting & IP Addressing:** Applied proper subnetting for efficient IP management.
- **Inter-VLAN Routing**: Configured router-on-a-stick for communication between VLANs.
- **DHCP Server Configuration**: Routers act as DHCP servers to dynamically assign IP addresses.
- **SSH Configuration**: Set up SSH for secure remote access to routers.
- **Switchport Security**: Applied port security on switches, especially for the IT department.
- **Wireless Network Setup**: Configured WLAN using Cisco Access Points for wireless devices.
- **Device Configuration:** Configured all host devices to ensure seamless communication.
- **Testing & Verification**: Thoroughly tested the network to verify communication across all devices.

## How to Use
- Download the project files and open them in Cisco Packet Tracer.
- Review the configurations for routers, switches, and wireless access points.
- Test the network communication using the provided topology.
## Conclusion
This project provides a detailed and practical approach to designing and implementing a secure and efficient network for a modern hotel. It showcases a range of networking technologies and best practices, making it a great reference for network design and implementation.
