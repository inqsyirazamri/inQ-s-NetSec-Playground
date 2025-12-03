# inQ-s-NetSec-Playground
A continuation of "learning security my way” journey, where I focus on network security labs through the lens of OSI layers. Each lab includes a PDF or packet tracer file documenting objectives, steps, configurations, and/or observations.

*Notes:*
* Labs cover various tools and technologies depending on the scenario—Cisco, pfSense, GNS3, Wireshark, and more.
* Each lab demonstrates practical application of network security concepts and/or threat detection techniques.
 
## Contents

### 1. Firewall & VPN Labs

| Lab                                               | Description                                                                    |
| ------------------------------------------------- | ------------------------------------------------------------------------------ |
| ASA Site Config – NAT_DHCP_SSH_ACL.pka            | Configured ASA as an edge device with NAT, DHCP, AAA, SSH, and DMZ access.     |
| Implement Site-to-Site IPsec VPN.pkt              | Set up secure LAN-to-LAN VPN with IPsec encryption, ACLs, and routing.         |
| Provision pfSense Firewall with Snort IDS_IPS.pdf | Configured pfSense firewall and integrated Snort IDS/IPS for threat detection. |
| Snort IDS and Firewall Rule Tuning.pdf            | Tuned IDS/firewall rules, monitored alerts, and verified threat blocking.      |

### 2. ACL & Security Policy Labs
   
| Lab                                             | Description                                                                |
| ----------------------------------------------- | -------------------------------------------------------------------------- |
| Implement Extended ACLs – Scenarios 1 & 2.pka   | Applied Layer 3/4 ACLs to filter traffic based on IP, protocol, and ports. |
| Implement Named/Numbered Standard IPv4 ACLs.pka | Configured standard ACLs for IP-based traffic filtering.                   |
| Implement VLAN Security.pka                     | Applied VLAN security to restrict unauthorized access at Layer 2.          |
| Implement Port Security.pka                     | Configured port security to limit access on network switches.              |
| Implement STP Security.pka                      | Secured spanning tree protocol to prevent topology attacks.                |
| Implement AAA TACACS+ RADIUS.pkt                | Configured AAA protocols for centralized access control.                   |

### 3. Routing & Network Protocol Labs
   
| Lab                                        | Description                                                                               |
| ------------------------------------------ | ----------------------------------------------------------------------------------------- |
| Implement OSPF.pkt                         | Configured OSPF routing protocol for network connectivity and path optimization.          |
| Packet Analysis in GNS3 with Wireshark.pdf | Captured and analyzed network traffic in a virtual lab to identify anomalies and attacks. |

### Extra: Reference Materials
| Name                                                   | Description                                                          |
| ----------------------------------------------------- | -------------------------------------------------------------------- |
| All-in-One Digital Forensics Tutorial Compilation.pdf | eForensics Magazine 2020 reference for digital forensics techniques. |
| Attacking Network Protocols – A Hacker Guide.pdf      | Book on network protocol capture, analysis, and exploitation.        |


