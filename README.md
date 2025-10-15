Of course. Here is a comprehensive `README.md` file for your GitHub repository, created based on the project report you provided. You can copy and paste this directly into a `README.md` file in your repository.

-----

```markdown
# Metropolitan Area Network (MAN) Simulation

[cite_start]This project is a comprehensive simulation of a Metropolitan Area Network (MAN) designed for the "Data Communications and Computer Networks" course at Dokuz Eylül University[cite: 1, 5, 6, 7]. The network was built and simulated using **Cisco Packet Tracer**.

**Authors:**
* [cite_start]Yasamin Valishariatpanahi (2022510013) [cite: 14]
* [cite_start]Sara Mahyanbakhshayesh (2022510046) [cite: 14]

---

## About The Project

[cite_start]The goal of this project was to design, configure, and simulate a robust MAN that connects two distinct branch offices within a city through an Internet Service Provider (ISP)[cite: 33]. [cite_start]The network architecture is designed to be scalable and cost-effective, supporting various services and a diverse range of end-user devices. [cite: 45]

[cite_start]The topology includes routers, switches, servers, access points, and end devices configured to handle real-world networking scenarios like web hosting, file sharing, email communication, and VoIP calls. [cite: 34, 38, 40]

![General Design](https://i.imgur.com/83p09kX.png)
[cite_start]*(Image based on Figure 1: General Design of the System in the report)* [cite: 190]

### Key Features & Services

* [cite_start]**Network Topology**: A MAN connecting two branches, each with three distinct facilities, via a central ISP. [cite: 33]
* **Server Farm**: A dedicated facility hosting a variety of servers:
    * [cite_start]DHCP Server [cite: 260]
    * [cite_start]DNS Server [cite: 264]
    * [cite_start]Mail Server (SMTP/POP3) [cite: 262]
    * [cite_start]10 Web Servers (HTTP) [cite: 236, 238, 240, 242, 244, 247, 248, 253, 254, 265]
    * [cite_start]4 FTP Servers [cite: 266, 269, 271, 272]
* [cite_start]**Connectivity**: Support for both wired (Ethernet) and wireless devices, including PCs, laptops, smartphones, and tablets. [cite: 56, 57, 59]
* [cite_start]**IP Addressing**: A systematic IPv4 addressing scheme was implemented for all devices and subnets. [cite: 39]
* [cite_start]**Protocols Implemented**: Core networking protocols such as TCP/IP, DNS, DHCP, FTP, HTTP, SMTP, POP3, SSH, and SCCP (for VoIP) were configured and tested. [cite: 40, 69, 74, 75, 76, 77, 78, 82, 1952]

---

## Simulation Scenarios

The functionality and performance of the network were verified by simulating nine distinct user scenarios:

1.  [cite_start]**Email & Web Access**: A wireless user from Branch 2 reads emails and browses the web. [cite: 1018]
2.  [cite_start]**FTP File Transfer**: A computer engineer sends code files from a workstation in Branch 2 to an FTP server in Branch 1. [cite: 1609]
3.  [cite_start]**Internal VoIP Call**: Two users within the same facility in Branch 1 communicate via a VoIP call. [cite: 1908]
4.  [cite_start]**Email Access Denied**: An email attempt fails between two branches due to security permission restrictions, demonstrating access control. [cite: 2267]
5.  [cite_start]**Inter-Branch Ping Test**: A user in Branch 2 pings a web server in Branch 1 to test cross-branch connectivity. [cite: 2323]
6.  [cite_start]**Cross-Branch Email**: A laptop user in Branch 1 successfully sends an email to a friend in Branch 2. [cite: 2571]
7.  [cite_start]**Remote Server Access (SSH)**: A smartphone user in Branch 2 securely connects to a web server in Branch 1 using SSH. [cite: 2799]
8.  [cite_start]**Additional Scenario 1**: A tablet user receives and successfully replies to an email message. [cite: 3124]
9.  [cite_start]**Additional Scenario 2**: A VoIP user calls an unregistered number, resulting in an "Unknown Number" error. [cite: 3570]

---

## How to Use

To explore the network topology and run the simulations, open the `.pka` or `.pkz` design file using **Cisco Packet Tracer** software. The full project documentation and analysis can be found in the `Metropolitan Area Network Simulation Report.pdf` file.

```
