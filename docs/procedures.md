# Procedures (SOP)

## SOP-001: OS Installation (Ubuntu Server)
**Goal:** Install a stable server OS for lab operations.

### Steps
1. Create VM: 2 vCPU, 4GB RAM, 40GB disk
2. Mount ISO and boot
3. Set hostname, create admin user
4. Install OpenSSH server (recommended)
5. Reboot and login
6. Update packages:
   - `sudo apt update && sudo apt upgrade -y`

### Validation
- `hostname`
- `ip a`
- `ping -c 4 8.8.8.8`
- `ping -c 4 google.com`

### Rollback
- Restore VM snapshot 

