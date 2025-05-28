# 🏠 Smart Hostel System - Cisco Packet Tracer Project

The **Smart Hostel System** is a comprehensive network simulation developed using **Cisco Packet Tracer**. It emulates a modern hostel’s network infrastructure, integrating services such as secure internet access, IP surveillance, inter-room communication, and administrative connectivity. This simulation provides a scalable and secure network design suitable for educational or residential hostel environments.


<img width="1512" alt="Screenshot 2025-05-28 at 11 55 09 AM" src="https://github.com/user-attachments/assets/44907c91-2786-454f-afa3-728393ef9f10" />



## 📘 Project Overview

The **Smart Hostel System** is a comprehensive network simulation developed using **Cisco Packet Tracer**. It emulates a modern hostel’s network infrastructure, integrating services such as secure internet access, IP surveillance, inter-room communication, and administrative connectivity. This simulation provides a scalable and secure network design suitable for educational or residential hostel environments.


## 🧩 Features

- **Router and Switch Configuration**: Proper setup of routers and switches to manage network traffic efficiently.
- **Multiple VLANs**: Isolation of network segments for Admin, Students, and Surveillance to enhance security and traffic management.
- **DHCP**: Automatic IP address assignment to devices within the network.
- **Static and Dynamic Routing**: Implementation of routing protocols like RIP, OSPF, or EIGRP to facilitate communication between different network segments.
- **Wireless Access Points**: Provision of wireless connectivity for students and staff.
- **Server Setup**: Centralized servers providing DNS, DHCP, and web services.
- **Security Implementations**: Access Control Lists (ACLs) to restrict unauthorized access.
- **Smart Devices Integration**: Incorporation of IoT devices such as CCTV cameras and other smart appliances.


## 🚀 Getting Started

### Requirements

- Cisco Packet Tracer (version 8.0 or above recommended)

### How to Open

1. Launch Cisco Packet Tracer.
2. Open the file `smart_hostel_system.pkt`.
3. Explore the network topology and configurations.


## 🔧 Configuration Highlights

### Network Topology

- **Routers**: Configured with appropriate interfaces and routing protocols to manage inter-VLAN communication.
- **Switches**: Set up with VLANs to segregate network traffic.
- **Access Points**: Provide wireless connectivity to end devices.
- **Servers**: Host services like DHCP, DNS, and web applications.

### VLAN Configuration

- **VLAN 10**: Admin Department
- **VLAN 20**: Student Rooms
- **VLAN 30**: Surveillance Systems
- **VLAN 99**: Management VLAN

### IP Addressing Scheme

- VLAN 10: `192.168.10.0/24`
- VLAN 20: `192.168.20.0/24`
- VLAN 30: `192.168.30.0/24`
- VLAN 99: `192.168.99.0/24`

### Routing Protocols

- **Dynamic Routing**: Implemented using OSPF to facilitate efficient routing between VLANs.

### Security Measures

- **ACLs**: Configured to restrict access between VLANs, ensuring that sensitive information remains protected.
- **Port Security**: Implemented on switches to prevent unauthorized devices from connecting to the network.


## 📡 Use Case

This project is ideal for:

- Network design practice
- Academic demonstrations
- Hostel or residential facility IT planning
- Learning VLANs, routing, DHCP, and server integration


## 🙌 Credits

- **Developer**: Momeena Azhar  
- **Course**: Data Communication and Networking Lab


## 📄 License

This project is for educational use only.
