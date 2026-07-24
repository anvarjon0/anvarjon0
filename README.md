<div align="center">

<!-- Optsimallashtirilgan Minimalist Banner -->
<img src="YOUR_BANNER_LINK" alt="Infrastructure & Engineering Banner" width="100%" />

<br/><br/>

# 💻 ANVARJON OLIMJONOV
**System Architect | Senior Infrastructure & Network Specialist | Senior Backend Engineer**

*Designing resilient distributed systems, enterprise infrastructure, and high-performance backends.*

<p align="center">
  <a href="https://linkedin.com"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:your-email@domain.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-Uzbekistan-blue?style=flat-square&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Uptime-99.99%25-brightgreen?style=flat-square" />
</p>

</div>

---

### 🚀 Technical Overview

Ko'p yillik tajribaga ega bo'lgan mutaxassis sifatida enterprise darajadagi AT infratuzilmalarini loyihalash, tarmoq xavfsizligini ta'minlash va yuqori yuklamalarga chidamli (high-load) backend tizimlarni qurish bilan shug'ullanaman. 

* **Infrastructure & Virtualization:** Murakkab tarmoq marshrutlash (BGP/OSPF), VoIP/SIP trunking, VLAN segmentatsiyasi va Linux serverlar klasterizatsiyasi.
* **System Integration:** IP-kameralar (RTSP streaming), apparat va dasturiy ta'minot integrasiyasi, hardware-level POS va avtomatlashtirilgan terminallar bilan ishlash.
* **Backend Architecture:** Relatsion va Hujjatga yo'naltirilgan ma'lumotlar bazalarini muvozanatlash, ERP/CRM tizimlari uchun arxitektura va RESTful/gRPC API loyihalash.

---

### 🧰 Core Stack & Ecosystem

| Domain | Engineering Technologies & Protocols |
| :--- | :--- |
| **System & Kernel** | `Linux (Ubuntu/Debian, RHEL)`, `Bash/Shell Scripting`, `Systemd`, `Core Utilities` |
| **Networking & VoIP** | `Routing & Switching (Cisco)`, `Static Routing`, `VLANs`, `VoIP/SIP Trunking`, `WireGuard/OpenVPN`, `RTSP Streaming` |
| **Backend & Runtime** | `PHP / Laravel`, `Node.js / Express`, `Go`, `Python` |
| **Databases & Caching** | `PostgreSQL`, `MySQL`, `MongoDB`, `SQLite` |
| **DevOps & Infrastructure** | `Docker / Containerization`, `Nginx / Reverse Proxy`, `Git / CI/CD Pipelines`, `Monitoring` |

---

### 🏛 Infrastructure & Topology Architecture

```text
                                [ Public Internet ]
                                         │
                                   ┌─────┴─────┐
                                   │  Firewall │ (Ingress / Traffic Filtering)
                                   └─────┬─────┘
                                         │
                               ┌─────────┴─────────┐
                               │  Core Router/L3   │ (Static Routing / VoIP Trunk)
                               └─────────┬─────────┘
                                         │
                     ┌───────────────────┴───────────────────┐
                     │                                       │
            ┌────────┴────────┐                     ┌────────┴────────┐
            │  Managed Switch │                     │  Ubuntu Server  │ (Production Node)
            └────────┬────────┘                     └────────┬────────┘
                     │                                       │
       ┌─────────────┼─────────────┐               ┌─────────┴─────────┐
       │             │             │               │                   │
┌──────┴──────┐┌─────┴──────┐┌─────┴──────┐ ┌──────┴──────┐     ┌──────┴──────┐
│ IP Cameras  ││ VoIP Phones││ Client PCs │ │ Nginx Proxy │     │ PostgreSQL  │
│(RTSP Streams)│(SIP Trunking)││(LAN Nodes) │ └──────┬──────┘     └─────────────┘
└─────────────┘└────────────┘└────────────┘        │
                                            ┌──────┴──────┐
                                            │ Laravel App │
                                            └─────────────┘
