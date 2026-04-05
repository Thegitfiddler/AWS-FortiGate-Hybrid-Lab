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
