# IT7099 — Global Health Network (GHN) Project

This Repository sitory contains all working files, configurations, and documentation used throughout the **IT7099 CCNP Routing project**, titled the *Global Health Network (GHN) Project*.  
Everything here is meant to document the design, implementation, verification, and backups for a real multi-site enterprise network built and tested in a lab environment. 

---

## What’s in This Repository 

### 1) Network Configurations  
Full CLI configurations, backups, and device-specific files for all routers and switches across GHN sites:
- Bahrain
- England
- Luxembourg
- China
- ISP nodes  
These configs include routing protocols, WAN/VPN setups, security controls, and verification states. 

### 2) Design & Documentation Files
- **Network Topology**— Visual map of all GHN sites and connections. 
- Word/Doc notes explaining layout, addressing, and design decisions.

  ![Topology](Network%20Topolgy.png) 

### 3) Backup Files
Snapshots of device configs taken at key stages of testing and verification. 

### 4) System & Server Files
Supporting materials from the EVE-NG environment and other lab VMs (e.g., Windows Server, RADIUS, server roles). 

---

## Purpose & Scope

The goal of this project is to demonstrate real-world enterprise routing and multi-site connectivity using:
- Scalable routing protocols (OSPF, BGP, etc.)
- WAN technologies (DMVPN, eBGP/iBGP)
- IP addressing and segmentation
- Network verification and troubleshooting  
Everything here is practical work you can load into a simulator (like EVE-NG) and verify behavior using CLI commands. 

---

## How to Use This Repository 

**If you’re studying or reviewing this project:**
1. Open the **Network Topology** diagram to understand site layout.
2. Load the appropriate configurations into your simulator of choice.
3. Use the CLI configs and backups to step through:
   - Routing
   - Security
   - Connectivity checks
4. Compare your own setup against the configs in the Repository .


---

## Recommended Tools

- **EVE-NG** for topology/simulation
- Cisco CLI (IOL)  
- Ping, traceroute, and **show/debug** commands for verification

---

## Attribution

All work in this Repository was completed by Hussain Ali (Student ID: 202202674) as part of the IT7099 CCNP Route For A Global Health Network project.



