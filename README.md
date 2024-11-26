Projeto da etapa estadual da worldskills |  WorldSkills State Stage Project


Project Description:
This project, carried out as part of the SPSkills Module C competition, involved the full implementation and configuration of a multi-site corporate network using Cisco equipment and technologies. The objective was to build a robust, secure, and scalable network infrastructure, covering multiple locations (HQ1, HQ2, BR1, and BR2) and connecting them through WAN technologies such as FlexVPN and DMVPN.

Technologies and Tools:
Simulation Platform: EVE-NG
Cisco Equipment: Routers, Switches, Firewalls (ASAs) – Specify models if possible (e.g., Cisco ISR 4331 routers, Cisco Catalyst 2960 switches)
Routing Protocols: OSPFv2, OSPFv3, MP-BGP, RIP
Switching Protocols: VLANs (IEEE 802.1q), VTP, DTP, Spanning Tree (PVST)
WAN Technologies: FlexVPN (Hub-and-Spoke and Dual Hub Single Cloud DMVPN), IPSec
Network Services: DHCPv4, DHCPv6 (Stateless and Stateful), NTP, TACACS+, AAA
Network Security: Port Security, DHCP Snooping, Dynamic ARP Inspection, SSHv2
Challenges and Solutions:

Technology Integration: The project required the integration of multiple Cisco technologies, which demanded careful planning and a deep understanding of how each protocol and service interacts. The solution involved creating a step-by-step implementation plan and validating each stage before proceeding. Key challenges included ensuring compatibility between OSPF and BGP, and correctly configuring VRF for FlexVPN.

Security Configuration: Network security was a critical aspect of the project. The solution involved implementing multiple layers of security, including Port Security on access switches, DHCP Snooping to prevent DHCP spoofing attacks, Dynamic ARP Inspection to mitigate ARP poisoning attacks, and secure remote access configuration via SSHv2 with TACACS+ authentication.

Routing Optimization: The project required dynamic routing configuration to ensure efficient communication between locations. The solution involved optimizing OSPF and BGP protocols to minimize convergence time and ensure load balancing. Strategies included adjusting OSPF timers and configuring static routes for backup.

Troubleshooting: During implementation, some connectivity and performance issues arose. The solution involved using Cisco diagnostic tools (such as logs and debug commands) to identify and resolve issues.
