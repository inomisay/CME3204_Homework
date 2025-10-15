# Metropolitan Area Network (MAN) Simulation

This project is a comprehensive simulation of a Metropolitan Area Network (MAN) designed for the "Data Communications and Computer Networks" course at Dokuz Eylül University. The network was built and simulated using **Cisco Packet Tracer**.

**Authors:**
* Yasamin Valishariatpanahi (2022510013)
* Sara Mahyanbakhshayesh (2022510046)

---

## About The Project

The goal of this project was to design, configure, and simulate a robust MAN that connects two distinct branch offices within a city through an Internet Service Provider (ISP). The network architecture is designed to be scalable and cost-effective, supporting various services and a diverse range of end-user devices.

The topology includes routers, switches, servers, access points, and end devices configured to handle real-world networking scenarios like web hosting, file sharing, email communication, and VoIP calls.



### Key Features & Services

* **Network Topology**: A MAN connecting two branches, each with three distinct facilities, via a central ISP.
* **Server Farm**: A dedicated facility hosting a variety of servers:
    * DHCP Server
    * DNS Server
    * Mail Server (SMTP/POP3)
    * 10 Web Servers (HTTP)
    * 4 FTP Servers
* **Connectivity**: Support for both wired (Ethernet) and wireless devices, including PCs, laptops, smartphones, and tablets.
* **IP Addressing**: A systematic IPv4 addressing scheme was implemented for all devices and subnets.
* **Protocols Implemented**: Core networking protocols such as TCP/IP, DNS, DHCP, FTP, HTTP, SMTP, POP3, SSH, and SCCP (for VoIP) were configured and tested.

---

## Simulation Scenarios

The functionality and performance of the network were verified by simulating nine distinct user scenarios:

1.  **Email & Web Access**: A wireless user from Branch 2 reads emails and browses the web.
2.  **FTP File Transfer**: A computer engineer sends code files from a workstation in Branch 2 to an FTP server in Branch 1.
3.  **Internal VoIP Call**: Two users within the same facility in Branch 1 communicate via a VoIP call.
4.  **Email Access Denied**: An email attempt fails between two branches due to security permission restrictions, demonstrating access control.
5.  **Inter-Branch Ping Test**: A user in Branch 2 pings a web server in Branch 1 to test cross-branch connectivity.
6.  **Cross-Branch Email**: A laptop user in Branch 1 successfully sends an email to a friend in Branch 2.
7.  **Remote Server Access (SSH)**: A smartphone user in Branch 2 securely connects to a web server in Branch 1 using SSH.
8.  **Additional Scenario 1**: A tablet user receives and successfully replies to an email message.
9.  **Additional Scenario 2**: A VoIP user calls an unregistered number, resulting in an "Unknown Number" error.

---

## How to Use

To explore the network topology and run the simulations, open the `.pka` or `.pkz` design file using **Cisco Packet Tracer** software. The full project documentation and analysis can be found in the `Metropolitan Area Network Simulation Report.pdf` file.
