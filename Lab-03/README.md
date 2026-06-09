# Day 03 — OSI Model & Traffic Analysis (Simulation Mode)

**Date:** 2025-10-18  
**Author:** Balaji — NMS Engineer, Pace Digitek Ltd  

---

## 🎯 Lab Overview
Today’s lab focuses on understanding how real network traffic maps to the **OSI Model layers** using **Cisco Packet Tracer Simulation Mode**.

The goal is to visually observe packets, analyze protocols, and identify which OSI layers are involved during common network operations.

---

## 🖥️ Network Topology
- 1 × Server (SRV1)  
- 1 × PC (PC1)  
- 2 × Switches (2960)  
- 2 × Routers (R1, R2)  

**Networks used:**
- `192.168.1.0/24` (LAN segment)  
- `10.0.0.0/24` (WAN link between routers)

---

## 🧩 Lab Tasks Performed
1. Enabled **Simulation Mode** to monitor live packet flow.  
2. Observed traffic types such as:
   - ARP  
   - ICMP  
   - IP  
3. Released and renewed PC1’s IP address to generate **Layer 7 traffic**.  
4. Traced packets hop-by-hop across switches and routers.  
5. Mapped each protocol to its corresponding **OSI layer**.

---

## 🧠 OSI Layer Analysis
| OSI Layer | Observation |
|----------|------------|
| Layer 7 – Application | DHCP request/renew process |
| Layer 4 – Transport | UDP used during DHCP |
| Layer 3 – Network | IP addressing and routing |
| Layer 2 – Data Link | ARP requests and MAC resolution |
| Layer 1 – Physical | Frame transmission over links |

---

## 🖼️ Topology Screenshot
![Day-03 Lab Screenshot](Screenshot.png)

---

## 📂 Files
- `Day 03 Lab – OSI Model.pkt`  
- `Screenshot.png`

---

## 💡 Key Learnings
- Understood how real traffic maps to the OSI model layers.  
- Learned to use **Simulation Mode** for deep packet inspection.  
- Visualized ARP, DHCP, and ICMP behavior across devices.  
- Strengthened troubleshooting fundamentals for NOC/NMS roles.

---

📌 **Progress:** Day 03 of 60 — Building strong networking fundamentals step by step 🚀
