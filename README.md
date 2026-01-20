# datacenter-fundamentals-lab


## Overview
This repository documents my hands-on lab experience building and operating
a basic data center server environment. The lab focuses on real-world
data center technician tasks including server deployment, networking,
remote access, system health checks, troubleshooting, and documentation.

All configurations are performed in a lab environment and documented
using best practices to reflect production workflows.

---

## Skills Demonstrated
- Linux server deployment and administration
- Static IP configuration using Netplan
- Secure SSH remote access configuration
- Server health monitoring (CPU, memory, disk)
- Data center networking fundamentals (NICs, VLANs, switching)
- Troubleshooting using structured playbooks
- Professional documentation and change tracking

## Lab Environment
- Platform: VirtualBox
- OS: Ubuntu Server 22.04 LTS
- Server Name: DC-Server-01
- Network:
  - Static IP addressing
  - DNS configuration
  - Default routing
- Remote Access:
  - OpenSSH
  - Root login disabled

## Lab Deliverables (Evidence)
- ✅ Inventory: [docs/inventory.md](docs/inventory.md)
- ✅ Procedures / SOPs: [docs/procedures.md](docs/procedures.md)
- ✅ Troubleshooting Playbook: [docs/troubleshooting.md](docs/troubleshooting.md)
- ✅ Glossary: [docs/glossary.md](docs/glossary.md)
- ✅ Build Notes: [logs/build-notes.md](logs/build-notes.md)
- ✅ Network & Cabling Overview: [docs/network-and-cabling.md](docs/network-and-cabling.md)
- ✅ Architecture Diagram [Data Center Architecture](diagrams/topology.md) This diagram illustrates server connectivity, Top-of-Rack switching, routing, and firewall placement in a data center environment.

## Configuration Examples

This repository includes example configuration files used
to document how the lab environment was configured.

- Network static IP configuration (Netplan)
- SSH server hardening examples

All files are sanitized and provided for documentation purposes only.


## Quick Start (How to Reproduce)
1. Create a VM (2 vCPU / 4GB RAM / 40GB disk)
2. Install Ubuntu Server (or Windows Server)
3. Configure networking (static IP or DHCP)
4. Validate connectivity (ping gateway, DNS test, update packages)
5. Document issues and fixes in the troubleshooting playbook

## Roadmap
- Add a second VM and simulate a small rack environment
- Add monitoring basics (logs, uptime checks)
- Add basic automation (scripts for health checks)

## Author
Guively Noel  
📍 Georgia, USA  
🔗 GitHub: https://github.com/GuivelyNoel 
