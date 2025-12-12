# IT7099 — Global Health Network (GHN) Project

This repository contains all working files, configurations, and documentation used throughout the **IT7099 CCNP Routing project**, titled the *Global Health Network (GHN) Project*.  
Everything here is meant to document the design, implementation, verification, and backups for a real multi-site enterprise network built and tested in a lab environment. :contentReference[oaicite:0]{index=0}

---

## What’s in This Repo

### 1) Network Configurations  
Full CLI configurations, backups, and device-specific files for all routers and switches across GHN sites:
- Bahrain
- England
- Luxembourg
- China
- ISP nodes  
These configs include routing protocols, WAN/VPN setups, security controls, and verification states. :contentReference[oaicite:1]{index=1}

### 2) Design & Documentation Files
- **Network Topology.png** — Visual map of all GHN sites and connections. :contentReference[oaicite:2]{index=2}
- Word/Doc notes explaining layout, addressing, and design decisions. :contentReference[oaicite:3]{index=3}

### 3) Backup Files
Snapshots of device configs taken at key stages of testing and verification. :contentReference[oaicite:4]{index=4}

### 4) System & Server Files
Supporting materials from the EVE-NG environment and other lab VMs (e.g., Windows Server, RADIUS, server roles). :contentReference[oaicite:5]{index=5}

---

## Purpose & Scope

The goal of this project is to demonstrate real-world enterprise routing and multi-site connectivity using:
- Scalable routing protocols (OSPF, BGP, etc.)
- WAN technologies (DMVPN, eBGP/iBGP)
- IP addressing and segmentation
- Network verification and troubleshooting  
Everything here is practical work you can load into a simulator (like EVE-NG) and verify behavior using CLI commands. :contentReference[oaicite:6]{index=6}

---

## How to Use This Repo

**If you’re studying or reviewing this project:**
1. Open the **Network Topology** diagram to understand site layout.
2. Load the appropriate configurations into your simulator of choice.
3. Use the CLI configs and backups to step through:
   - Routing
   - Security
   - Connectivity checks
4. Compare your own setup against the configs in the repo.

This isn’t a plug-and-play “app” — it’s **working lab material** for review, replication, and study. :contentReference[oaicite:7]{index=7}

---

## Recommended Tools

- **EVE-NG** for topology/simulation
- Cisco CLI (IOS/IOS-XR/whatever image used)  
- Ping, traceroute, and **show/debug** commands for verification

---

## Attribution

All work in this repo was done by **Hussain Ali (Student ID: 202202674)** for the IT7099 CCNP route project. :contentReference[oaicite:8]{index=8}



