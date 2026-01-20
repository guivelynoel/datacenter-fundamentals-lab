# Data Center Network & Cabling Overview

## Purpose
This document explains how servers are physically and logically connected
in a typical data center environment, including cabling types, network
interfaces, switches, and traffic flow.

---

## Physical Network Components

### Network Interface Cards (NICs)
- Servers typically have one or more NICs.
- NICs provide physical connectivity between the server and the network.
- Common speeds:
  - 1 Gbps (entry-level / management)
  - 10 Gbps (common in modern data centers)
  - 25 Gbps / 40 Gbps (high-performance environments)

### Network Switches
- Servers connect to **Top-of-Rack (ToR)** switches.
- ToR switches aggregate traffic from multiple servers.
- Switches connect upstream to aggregation or core switches.

### Patch Panels
- Used for cable organization and labeling.
- Improve troubleshooting and reduce physical damage.

---

## Cabling Types

### Ethernet (Copper)
- Cat5e / Cat6 / Cat6a
- Common for short distances (within racks)
- Used for management networks and standard server connectivity

### Fiber Optic
- Single-mode (long distance)
- Multi-mode (shorter distance, higher bandwidth)
- Used for switch uplinks and inter-rack connections

---

## Logical Network Design

### IP Addressing
- Static IPs are commonly used for servers.
- Ensures predictable connectivity and easier troubleshooting.

### VLANs
- Used to segment traffic for security and performance.
- Common VLANs:
  - Management VLAN
  - Server VLAN
  - Storage VLAN

### Routing
- Traffic between VLANs is routed through switches or firewalls.
- Default gateway directs traffic outside the local network.

---

## Data Center Traffic Flow (Example)

1. Server NIC sends traffic through Ethernet cable
2. Traffic reaches Top-of-Rack switch
3. Switch forwards traffic based on VLAN and routing rules
4. Traffic reaches firewall or upstream router if external

---

## Best Practices

- Label all cables and ports
- Avoid tight cable bends
- Use structured cabling standards
- Separate power and data cables
- Maintain documentation for all network connections

---

## Lab Relevance

In this lab:
- Virtual NICs simulate physical NICs
- Virtual switches simulate Top-of-Rack switches
- Static IP configuration simulates production server setup
- Network troubleshooting mirrors real data center workflows
