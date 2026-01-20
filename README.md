# datacenter-fundamentals-lab


## Overview
This repository documents my hands-on lab work to build data center technician fundamentals:
server setup concepts, OS installation, basic networking, RAID/storage basics, and troubleshooting.
My goal is to demonstrate real-world operational thinking through clear documentation.

## What This Lab Covers
- Server hardware fundamentals (CPU/RAM/storage/NIC/PSU concepts)
- OS installation (ubuntu Server) in a lab environment
- Network basics (IP addressing, VLAN concept, connectivity tests)
- Storage basics (RAID concepts, disk health checks)
- Standard operating procedures (SOP mindset)
- Troubleshooting playbook and incident-style notes

## Tools Used
- Virtualization: VirtualBox 
- OS: Ubuntu Server 
- Networking: basic switch/router concepts, ping/traceroute/nslookup
- Documentation: Markdown, diagrams (draw.io)

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

