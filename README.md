#  Cybersecurity Portfolio — Salman

Hands-on network security labs built in EVE-NG, covering Palo Alto firewall, Cisco ISE, and Fortinet FortiGate. Each lab includes topology diagrams, device configs, and troubleshooting notes.

>  Currently studying toward: **PCNSA** (Palo Alto) · **NSE 4** (Fortinet) · **Cisco ISE Specialist**

---

## 📁 Lab Index

###  Palo Alto Firewall (PAN-OS)

| # | Lab | Topics Covered | Status |
|---|-----|---------------|--------|
| 01 | Basic Setup & Interface Config | Zones, L3 interfaces, routing |  In Progress |
| 02 | Security Policies | Rule ordering, app-based rules, default deny |  Upcoming |
| 03 | NAT Policies | Source/dest NAT, U-turn NAT |  Upcoming |
| 04 | GlobalProtect VPN | Portal, gateway, split tunnel |  Upcoming |
| 05 | SSL Decryption | Forward proxy, exclusions |  Upcoming |

###  Cisco ISE

| # | Lab | Topics Covered | Status |
|---|-----|---------------|--------|
| 01 | Initial Setup & Admin Access | Node config, certificates |  Upcoming |
| 02 | RADIUS Authentication | Network devices, test auth |  Upcoming |
| 03 | 802.1X Wired | Auth policy, switch config |  Upcoming |

###  Fortinet FortiGate

| # | Lab | Topics Covered | Status |
|---|-----|---------------|--------|
| 01 | Basic Setup & Policies | Interfaces, zones, firewall rules |  Upcoming |
| 02 | IPSec VPN | Site-to-site, IKEv2, tunnel monitor |  Upcoming |
| 03 | Web Filtering & App Control | Security profiles, categories |  Upcoming |

###  Multi-Vendor Integration

| # | Lab | Topics Covered | Status |
|---|-----|---------------|--------|
| 01 | PA + ISE User-ID Integration | User-ID agent, identity policy |  Upcoming |
| 02 | Full Office Network Simulation | PA + FortiGate + ISE together | Upcoming |

---

##  Lab Environment

- **Platform:** EVE-NG Community Edition
- **Palo Alto:** PAN-OS VM-Series (trial)
- **Fortinet:** FortiGate VM (trial)
- **Cisco:** ISE trial / CML
- **Diagram tool:** draw.io

---

##  Each Lab Contains

- `README.md` — objective, topology, steps, what broke & how I fixed it
- `topology.png` — network diagram
- `configs/` — sanitised device configuration files
- `screenshots/` — key results and log outputs

---

##  How to Navigate

Each vendor has its own folder. Inside each folder, labs are numbered in order of complexity — start from `01` and work forward.

---

## Progress Timeline

Started: May 2026 | Target cert date: Nov 2026

---

*All configs are sanitised — no real IPs, credentials, or sensitive data.*
