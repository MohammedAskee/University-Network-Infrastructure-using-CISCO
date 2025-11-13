# 🧩 Network Infrastructure Design Proposal for a University

**Course:** COMP 352L — Computer Networks Lab  
**Semester:** 6th (Spring 2025)  
**Institute:** Pak-Austria Fachhochschule: Institute of Applied Sciences and Technology, Haripur, Pakistan  
**Department:** School of Computing Sciences  

---

## 👥 Team Members
- **Iqbal Mohammed Askee** (B22F0758CS143)  
- **Azeem Mohamed Hussain** (B22F0759CS142)  
- **Abdhur Rahman Nasir** (B22F0760CS141)

**Submitted To:** Mr. Muhammad Usman  
**Lab Instructor:** Mr. Ameer Hamza  

---

## 📘 Project Overview
This project presents a **basic yet functional network infrastructure design** for a university.  
It focuses on core networking technologies such as **VLANs**, **Routing**, **DHCP**, **DNS**, **NAT/PAT**, **Access Control Lists (ACLs)**, and **TELNET**.  
The goal is to provide **structured connectivity** across various university departments, labs, and administrative units while maintaining **security, manageability, and scalability**.

---

## 🎯 Objectives
- Design a **simple, secure, and scalable** network.
- Implement **VLANs** for logical segmentation.
- Use **Static and Dynamic Routing** for inter-department connectivity.
- Configure **DHCP and DNS** for automatic IP and name resolution.
- Apply **NAT/PAT** for shared internet access.
- Enforce **ACLs** for access control.
- Enable **TELNET** for remote network device management.
- Demonstrate **Inter-VLAN routing** for controlled communication.

---

## 🏗️ Proposed Network Design
### Topology Summary
- **Router:** Handles Inter-VLAN routing, NAT/PAT, and internet connectivity.  
- **Layer 3 Switch:** Optional, for additional VLAN routing support.  
- **Access Switches:** Connect labs, departments, and administrative blocks.  
- **Server:** Simulates DHCP, DNS, and Web services.  
- **End Devices:** PCs, printers, and wireless clients across departments.

---

## 🧱 VLAN Plan (Example)
| VLAN ID | VLAN Name | Use / Location |
|----------|------------|----------------|
| 10 | CS Lab A–C | 145 PCs total |
| 20 | Other Departments | Dept A & B (20 PCs each) |
| 30 | Students | Wi-Fi and general access |
| 40 | Faculty | 35 members |
| 50 | Admin Block | 50 users |
| 60 | Library | 30 users |
| 70 | IT Center | 10 professionals |
| 99 | Management VLAN | For network device management |

---

## ⚙️ Key Configurations
- **Subnetting:** Private IPs (192.168.x.0/24 per VLAN)
- **Routing:** Static or Dynamic (RIP/OSPF)
- **NAT/PAT:** Internet sharing using a single public IP
- **ACLs:** Restrict Student VLAN access to Admin VLAN
- **TELNET:** Secure remote device access
- **Server Setup:** DHCP, DNS, and Web server simulation

---

## 🧩 Tools & Devices
| Device | Quantity | Role |
|---------|-----------|------|
| Routers | 1–2 | Inter-VLAN, NAT, Routing |
| L3 Switch | 1 | VLAN and routing (optional) |
| L2 Switches | 5–6 | Departmental connectivity |
| End Devices | ~350 | PCs and other clients |
| Server | 1 | DHCP, DNS, Web Services |

---

## 📈 Conclusion
This project provides a **structured and educational approach** to network design using **Cisco Packet Tracer**.  
It integrates fundamental **CCNA-level concepts** such as subnetting, VLAN configuration, routing, and access control — offering both theoretical and practical understanding of network infrastructure in an academic environment.

---

**© 2025 — Pak-Austria Fachhochschule, Haripur**
