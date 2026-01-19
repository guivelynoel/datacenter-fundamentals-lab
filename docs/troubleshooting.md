# Troubleshooting Playbook

## Issue 001 — No Internet Connectivity After Install
**Symptoms**
- Cannot ping 8.8.8.8
- `apt update` fails

**Checks**
- `ip a` (is the interface up?)
- `ip r` (default route exists?)
- VM network mode (NAT/Bridged)

**Fix**
- Set correct adapter mode
- Restart network or renew DHCP

**Result**
- Connectivity restored and updates completed.

---------------------------------------------------

## Issue 002 — DNS Not Resolving
**Symptoms**
- Can ping 8.8.8.8 but cannot ping google.com

**Checks**
- `cat /etc/resolv.conf`
- `nslookup google.com`

**Fix**
- Update DNS settings to valid DNS servers
- Restart resolver service

**Result**
- DNS resolution restored.

## Issue 003 — Netplan Warnings After Static IP Configuration

**Symptoms**
- Warning: permissions too open
- Warning: gateway4 deprecated

**Cause**
- Netplan config file had insecure permissions
- Legacy gateway syntax used

**Fix**
- Set file permissions to 600
- Replaced gateway4 with default route syntax

**Result**
- Clean netplan apply with no warnings
- Static IP configured using best practices





