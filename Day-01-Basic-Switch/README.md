# Day 01 - Basic Switch Configuration

## 📖 Overview

This is the first lab in my **90-Day Cisco Packet Tracer Challenge**.

In this lab, I configured a Cisco 2960 switch, assigned IPv4 addresses to two PCs, and verified successful communication using the ping command.

---

## 🎯 Objective

* Configure a Cisco switch
* Connect two end devices
* Assign IPv4 addresses
* Verify network connectivity

---

## 🛠 Devices Used

* Cisco 2960 Switch
* PC0
* PC1

---

## 🌐 IP Addressing

| Device | IP Address   |
| ------ | ------------ |
| PC0    | 192.168.1.10 |
| PC1    | 192.168.1.20 |

Subnet Mask: **255.255.255.0**

---

## ⚙️ Configuration

```bash
enable
configure terminal

hostname SW1

interface range fa0/1-2
description Connected_to_PCs
no shutdown

end

copy running-config startup-config
```

---

## ✅ Verification

Successful ping between PC0 and PC1 confirmed Layer 2 connectivity.

---

## 📸 Screenshots

* Network Topology
* Switch Configuration
* Successful Ping

---

## 📚 Skills Learned

* Cisco Packet Tracer
* Cisco IOS CLI
* Basic Switch Configuration
* IPv4 Addressing
* Ping Verification

---

## 🚀 Challenge

This lab is part of my **90-Day Cisco Packet Tracer Challenge** to strengthen my networking skills and prepare for a Network Engineer role.
