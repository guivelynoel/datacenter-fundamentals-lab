# datacenter-fundamentals-lab


## Overview
This repository documents my hands-on lab work to build data center technician fundamentals:
server setup concepts, OS installation, basic networking, RAID/storage basics, and troubleshooting.
My goal is to demonstrate real-world operational thinking through clear documentation.

## What This Lab Covers
- Server hardware fundamentals (CPU/RAM/storage/NIC/PSU concepts)
- OS installation (Linux or Windows Server) in a lab environment
- Network basics (IP addressing, VLAN concept, connectivity tests)
- Storage basics (RAID concepts, disk health checks)
- Standard operating procedures (SOP mindset)
- Troubleshooting playbook and incident-style notes

## Tools Used
- Virtualization: VirtualBox / VMware / Proxmox (choose one)
- OS: Ubuntu Server / Windows Server (choose one)
- Networking: basic switch/router concepts, ping/traceroute/nslookup
- Documentation: Markdown, diagrams (draw.io)

## Lab Deliverables (Evidence)
- ✅ Inventory: [docs/inventory.md](docs/inventory.md)
- ✅ Procedures / SOPs: [docs/procedures.md](docs/procedures.md)
- ✅ Troubleshooting Playbook: [docs/troubleshooting.md](docs/troubleshooting.md)
- ✅ Glossary: [docs/glossary.md](docs/glossary.md)
- ✅ Build Notes: [logs/build-notes.md](logs/build-notes.md)

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

