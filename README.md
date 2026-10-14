# TechNova Ltd Network Configuration and Security Project

This project demonstrates the design and configuration of a departmental network for TechNova Ltd using Cisco Packet Tracer. It enables communication between the IT, Sales, and HR departments while implementing Access Control Lists (ACLs) to restrict unauthorized network access without preventing Sales employees from accessing the IT server's HTTP services.

## Table of Contents
- Project Overview
- Network Topology
- Tools and Technologies
- Configuration Steps
- Results and Findings
- Author

## Project Overview

The purpose of this project is to configure a secure network infrastructure for TechNova Ltd that supports communication among the IT, Sales, and HR departments while enforcing basic network access restrictions.

The project focuses on the following objectives:

- Enable communication between the three departments.
- Configure IP addressing and Dynamic Host Configuration Protocol (DHCP).
- Set up an IT server with HTTP and FTP services.
- Implement an Access Control List (ACL) to restrict specific network traffic.
- Test network connectivity and verify that security rules function as intended.

The configuration demonstrates fundamental networking concepts, including network segmentation, IP addressing, DHCP, server services, connectivity testing, and access control.

## Network Topology

The network was designed and simulated using Cisco Packet Tracer. It consists of three departmental networks connected through a router, with each department having its own switch and two PCs.

**Network components:**

- **Router:** One Cisco 2911 router to facilitate communication between departmental networks and enforce access control.
- **Switches:** Three Cisco 2960 switches, providing network connectivity for the departmental devices.
- **End devices:** Six PCs, with two PCs assigned to each department.
- **IT server:** A server configured to provide HTTP and FTP services.

**Departmental layout:**

- **IT Department:** Two PCs and an IT server connected through a departmental switch.
- **Sales Department:** Two PCs connected through a departmental switch.
- **HR Department:** Two PCs connected through a departmental switch.
- **Routing and security:** The Cisco 2911 router connects the departmental networks and applies an ACL to restrict Sales-to-IT ping traffic while allowing access to the server's HTTP service.

**IP addressing:**

IP addressing and DHCP were configured for the network. The project document includes screenshots of the IP configuration for representative PCs in the IT, Sales, and HR departments. However, the specific IP addresses, subnet masks, default gateways, and DHCP ranges are not documented in the available text.

## Tools and Technologies

- **Cisco Packet Tracer** — Network design, simulation, configuration, and connectivity testing.
- **Cisco 2911 Router** — Inter-network routing and ACL enforcement.
- **Cisco 2960 Switches** — Departmental network connectivity.
- **DHCP (Dynamic Host Configuration Protocol)** — IP address configuration for network devices.
- **Access Control Lists (ACLs)** — Traffic filtering and network access restrictions.
- **HTTP (Hypertext Transfer Protocol)** — Web service hosted on the IT server.
- **FTP (File Transfer Protocol)** — File transfer service configured on the IT server.
- **Ping** — Network connectivity testing and verification.
- **Router Command-Line Interface (CLI)** — Router configuration and ACL implementation.

## Configuration Steps

1. **Design the network topology.**  
   Created the TechNova Ltd network in Cisco Packet Tracer using one Cisco 2911 router, three Cisco 2960 switches, six PCs, and an IT server.

2. **Configure IP addressing and DHCP.**  
   Configured IP addressing and DHCP to support communication among the departmental devices. Verified the IP configuration of representative PCs in the IT, Sales, and HR departments.

3. **Configure the IT server.**  
   Enabled the HTTP and FTP services on the IT server to provide web and file transfer functionality.

4. **Establish departmental connectivity.**  
   Configured the network to enable communication between the IT, Sales, and HR departments through the router.

5. **Implement an Access Control List (ACL).**  
   Applied an ACL on the router to prevent Sales PCs from pinging the IT network while allowing access to the IT server's services.

6. **Test connectivity from the HR department.**  
   Executed a ping test from an HR PC to an IT PC. The successful response confirmed that communication between these devices was working as expected.

7. **Test the security restriction from the Sales department.**  
   Executed a ping test from a Sales PC to an IT PC. The ping failed as intended, demonstrating that the ACL restriction was functioning.

8. **Verify HTTP service access.**  
   Tested access to the IT server's HTTP service from the Sales department. The successful access confirmed that the security restriction did not prevent Sales users from accessing the web service.

9. **Review the configuration and results.**  
   Examined the router's ACL configuration and the connectivity test results to verify that the network supported the intended communication and security requirements.

## Results and Findings

The network was successfully configured to support communication between the IT, Sales, and HR departments while enforcing basic security controls.

**Key results:**

- **Successful network connectivity:** An HR PC successfully pinged an IT PC, confirming communication between the two devices.
- **Effective access restriction:** A Sales PC could not ping an IT PC, confirming that the configured ACL blocked the specified traffic.
- **HTTP service accessibility:** Sales users could successfully access the HTTP service hosted on the IT server despite the ping restriction.
- **DHCP and IP configuration:** IP addressing and DHCP were configured as part of the network setup.
- **Server service configuration:** HTTP and FTP services were configured on the IT server.
- **Improved network security:** The ACL demonstrated how network traffic can be restricted according to departmental access requirements while preserving access to permitted services.

**Conclusion**

The TechNova Ltd network configuration project successfully demonstrated the implementation of departmental connectivity and basic network security using Cisco Packet Tracer. By combining IP addressing, DHCP, server services, connectivity testing, and ACL-based traffic filtering, the project established a foundation for controlling network access and supporting stronger security measures in the future.

## Author

**Bolarinwa Olufunwa**

- **Role:** Network Technician
- **Project:** TechNova Ltd Network Configuration and Security
- **Project Date:** October 5, 2026
