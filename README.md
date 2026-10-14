# Cisco Packet Tracer Multi-Network Configuration Project

This project demonstrates the design, configuration, and testing of a **multi-network environment using Cisco Packet Tracer**. The network was configured with multiple IPv4 subnets, DHCP addressing, HTTP and FTP services, router interfaces, access control rules, and connectivity testing to demonstrate practical networking and security concepts. networkinggg assignment

## Table of Contents
- Project Overview
- Network Topology
- Tools and Technologies
- Configuration Steps
- Results and Findings
- Author

## Project Overview

The purpose of this project was to build and configure a functional network environment in **Cisco Packet Tracer** and demonstrate key networking concepts including **IPv4 addressing, subnetting, DHCP, routing, HTTP, FTP, Access Control Lists (ACLs), and network connectivity testing**.

The project also involved verifying network configurations using command-line tools such as `ipconfig` and `ping`, testing access to network services, and observing how security rules affect communication between devices.

## Network Topology

The network consists of multiple LAN segments connected through networking devices, with PCs and a server distributed across separate IPv4 networks. networkinggg assignment

The main networks configured were:

- **192.168.10.0/24**
  - Default Gateway: **192.168.10.1**
  - Server: **192.168.10.2**
  - Client devices received addresses including **192.168.10.3** and **192.168.10.4**

- **192.168.20.0/24**
  - Default Gateway: **192.168.20.1**
  - Client devices received addresses including **192.168.20.2** and **192.168.20.3**

- **192.168.30.0/24**
  - Default Gateway: **192.168.30.1**
  - Client devices received addresses including **192.168.30.2** and **192.168.30.3**

- All three networks used the subnet mask **255.255.255.0**
- Client devices were configured to obtain IPv4 addressing through **DHCP**
- The server at **192.168.10.2** provided network services including **HTTP and FTP** networkinggg assignment

## Tools and Technologies

- **Cisco Packet Tracer**
- Cisco Router
- Network switches
- PCs / end-user devices
- Server
- **IPv4**
- **DHCP**
- **HTTP**
- **FTP**
- **Access Control Lists (ACLs)**
- **TCP/IP networking**
- Cisco IOS Command Line Interface
- `ipconfig`
- `ping`
- FTP command-line client

## Configuration Steps

1. Created the network topology in **Cisco Packet Tracer** using routers, switches, PCs, and a server.

2. Connected the network devices to create separate LAN segments for the **192.168.10.0/24**, **192.168.20.0/24**, and **192.168.30.0/24** networks.

3. Configured the required router interfaces and assigned the appropriate gateway addresses for each network.

4. Configured the server with the static IPv4 address **192.168.10.2**, subnet mask **255.255.255.0**, and default gateway **192.168.10.1**. networkinggg assignment

5. Configured client devices to use **DHCP** and verified that they received addresses from their respective subnets. networkinggg assignment

6. Used the `ipconfig` command on client PCs to verify assigned IPv4 addresses, subnet masks, and default gateways. networkinggg assignment

7. Enabled and configured the **HTTP service** on the server and created an internal company webpage for **NetCore Systems Ltd.** networkinggg assignment

8. Tested the HTTP server by navigating to `http://192.168.10.2` from a client web browser and confirmed that the internal webpage loaded successfully. networkinggg assignment

9. Enabled the **FTP service** on the server and configured an FTP user with permissions including read, write, delete, rename, and list access. networkinggg assignment

10. Tested FTP connectivity using `ftp 192.168.10.2` and successfully authenticated to the FTP server. networkinggg assignment

11. Configured an **extended Access Control List (ACL)** named `SALES_TO_IT` on the router.

12. Added ACL rules to deny selected ICMP traffic from the **192.168.20.0/24** network to the **192.168.10.0/24** network while permitting other IP traffic. networkinggg assignment

13. Applied the `SALES_TO_IT` ACL to the appropriate router interface.

14. Used the `ping` command to test communication between devices on different networks.

15. Verified that permitted network communication succeeded while traffic restricted by the ACL produced **Destination host unreachable** or unsuccessful ping results. networkinggg assignment

## Results and Findings

The project successfully demonstrated the configuration and testing of a segmented network environment using **Cisco Packet Tracer**.

- Devices successfully received IPv4 addresses through **DHCP**.
- The three network ranges were configured as **192.168.10.0/24**, **192.168.20.0/24**, and **192.168.30.0/24**.
- `ipconfig` was successfully used to verify client network configurations.
- The internal **HTTP server** at `192.168.10.2` was successfully accessed through a client web browser.
- An **FTP connection** to `192.168.10.2` was successfully established and authenticated.
- Successful `ping` tests demonstrated connectivity where communication was permitted.
- Failed ping tests demonstrated how routing and **ACL restrictions** can prevent communication between selected network segments.
- The project provided practical experience with **network configuration, troubleshooting, access control, network services, and connectivity verification**. networkinggg assignment

## Author

**Michael Olusola-Esan**

- **Field:** Governance, Risk and Compliance (GRC)
- **Location:** London, England
- **GitHub:** [Add GitHub Profile]
- **LinkedIn:** [Add LinkedIn Profile]
- **Email:** [Add Professional Email]
