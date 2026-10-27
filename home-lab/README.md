# SOC Home Lab — Wazuh on Kali (Single-VM Build)

## Overview
A self-built security monitoring lab using Wazuh, deployed via Docker,
running on a single Kali Linux VM that acts as both the monitored system
and the attack source. Rebuilt from an earlier three-VM attempt that
proved too resource-heavy for available hardware - redesigned into a
lighter, single-VM architecture that still demonstrates real detection.

## Architecture
- One Kali Linux VM running: SSH server (the monitored service), Docker,
  and Wazuh's Manager, Indexer, and Dashboard containers
- Attacks are simulated against the VM's own SSH service (localhost),
  removing the need for separate target/attacker machines

## Tools & Technologies
- Wazuh 4.9.2 (SIEM)
- Docker & Docker Compose
- Kali Linux
- OpenSSH Server
- Hydra (attack simulation)

## Build Log
1. [VM Setup](./01-vm-setup.md)
2. [SSH and Docker Install](./02-ssh-and-docker-install.md)
3. [Wazuh Deployment](./03-wazuh-deployment.md)
4. [RAM Troubleshooting](./04-ram-troubleshooting.md)

## Why the Redesign
The original lab used three separate VMs (manager, target, attacker),
which required internal network configuration and consistently exceeded
available RAM, leading to repeated crashes and an unrecoverable VM state.
Redesigning around a single VM removed the networking complexity entirely
while preserving the same core learning outcome: real SIEM deployment and
real attack detection.
