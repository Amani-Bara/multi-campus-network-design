# 🌐 Multi-Campus Network Design

This project was completed as part of **CS2091 – Computer Networks (Spring 2023)**.  
It designs and simulates a secure **multi-campus network** connecting **King Faisal University** and **Effat University** using **Cisco Packet Tracer**.  


---

## 📘 Project Overview

The goal was to design and implement a computer network connecting two universities across different logical areas, with support for labs, departments, servers, and inter-campus communication.  

Key features:
- Two universities:
  - **King Faisal University** → Departments: Medicine, Science, Business
  - **Effat University** → Departments: Engineering, Business
- Each lab is equipped with a **PC** and a **laptop**.
- Integrated services: **DHCP**, **DNS**, **Web server**, **Email server**.
- Multiple switches and routers ensure connectivity between labs, departments, and campuses.
- Cross-university communication verified using **Packet Tracer ping tests**.

---

## 🖥️ End Devices
- PCs and laptops in each lab
- DHCP server for automatic IP assignment
- DNS server for domain name resolution
- Web server (Effat University website)
- Email server for staff and students

---

## 🔧 Intermediate Devices
- **Switch hierarchy**:
  - Lab-level switches
  - Departmental switches
  - Core switch linking departments to the router
- **Routers**:
  - Router 1: King Faisal University
  - Router 2: Effat University
  - Router 3: Email server connection
- Routers interconnected for seamless data transfer

---

## 📡 Servers
- **DHCP Server** → automatic IP addressing  
- **DNS Server** → resolves domain names  
- **Web Server** → hosts Effat University’s site  
- **Email Server** → enables email communication between staff/students  

---

## 🔍 Testing & Verification
- Packet Tracer was used to verify:
  - LAN communication
  - Inter-campus connectivity (PC0 in LAN1 → PC8 in LAN2)
  - Successful configuration of DHCP, DNS, Email, and Web servers
- Screenshots demonstrate working connections and PDUs.

---

## 📊 Tools & Technologies
- Cisco Packet Tracer  
- Networking concepts: LAN, DHCP, DNS, Web/Email servers  
- Routers, switches, and server configuration  

---

## 📄 Files in this Repository
- `FinalProject_CS2091_Spring2023-Summary.pdf` — Project report with design, configurations, and screenshots  
- (Optional) `MultiCampusDesign.pkt` — Cisco Packet Tracer file if available  
- `README.md` — Documentation  

---

## 📜 License
This project is for academic use (Effat University, CS2091).  
Feel free to reference or adapt for learning purposes.
