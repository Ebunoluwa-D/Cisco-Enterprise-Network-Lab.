# Cisco Enterprise Network Lab

##  Project Overview
This project demonstrates a fully functional enterprise network designed in Cisco Packet Tracer. It features a hardened Branch Office connected to an HQ Data Center, focusing on security, scalability, and redundancy.

##  Key Technical Features
* **Layer 2 Segmentation:** Configured **VLANs 10 (Staff)** and **20 (Guest)** to isolate sensitive traffic.
* **Inter-VLAN Routing:** Implemented **Router-on-a-Stick** using sub-interfaces to bridge communication between subnets.
* **Security (ACLs):** Developed **Standard and Extended Access Control Lists** to block Guest access to the management plane and Staff devices.
* **Dynamic Routing:** Utilized **OSPF** to manage routing tables across the "Square" topology.
* **Edge Services:** Configured **NAT/PAT** on the HQ Gateway to provide internet access to private subnets.

##  Verification & Testing
* **SSH Management:** Staff devices successfully access the router via SSH, while Guest attempts are "Connection Refused" by ACLs.
* **Connectivity:** Verified end-to-end communication between the Branch and the HQ Server.
