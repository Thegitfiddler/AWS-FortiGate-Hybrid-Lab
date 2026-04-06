📌 Project Description

This project demonstrates a hybrid cloud network architecture integrating on-premises infrastructure with AWS using a FortiGate firewall and Cisco switch.

The environment includes VLAN-based network segmentation, secure management access, and a Site-to-Site IPsec VPN connection to an AWS VPC.

Key components include:

Cisco 2960X switch configured with VLANs (10, 20, 30, 40, 50, 99)
FortiGate 60F firewall handling inter-VLAN routing and security policies
Dedicated management VLAN (VLAN99) for secure administrative access
AWS VPC with public and private subnets
Site-to-Site VPN connection (VPN_Fortigate_Lab) linking on-prem VLAN20 to AWS private subnet

This lab simulates a real-world hybrid cloud architecture and reinforces concepts required for AWS Security Specialty and Azure AZ-500 certifications, including:

Network segmentation and isolation
Firewall policy enforcement (implicit deny model)
Hybrid connectivity using IPsec VPN
Routing between on-prem and cloud environments

<img width="2490" height="396" alt="image" src="https://github.com/user-attachments/assets/976b5c8e-6a43-45ce-8c19-53a6d92c0458" />
<img width="1245" height="198" alt="Screenshot 2026-04-06 at 3 33 12 AM" src="https://github.com/user-attachments/assets/09f3d9f7-4247-4ac0-bb68-89117c754064" />
<img width="1138" height="688" alt="image" src="https://github.com/user-attachments/assets/8bc087da-db7b-4465-b4ae-539a97955198" />
