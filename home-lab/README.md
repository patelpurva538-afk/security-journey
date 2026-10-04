# SOC Home Lab — Wazuh SIEM (Docker Deployment)

## Overview
A self-built security monitoring lab using Wazuh, deployed via Docker, to
detect and investigate simulated attacks in an isolated environment. Built
to apply skills from TryHackMe's Pre Security and SOC Level 1 paths
independently, without guided instructions — closer to how a real SOC
environment is set up and operated.

## Architecture
- **Wazuh Manager** — Ubuntu 26.04 LTS VM, running Wazuh's Manager,
  Indexer, and Dashboard as Docker containers
- **Target machine** — a monitored endpoint reporting activity to the
  Wazuh Manager
- **Attacker machine** — Kali Linux, used to generate real attack traffic
  (e.g. brute-force attempts) against the target
- All VMs run in an isolated internal network, separate from the host
  machine and the internet

## Tools & Technologies
- Wazuh 4.9.2 (SIEM)
- Docker & Docker Compose
- VirtualBox
- Ubuntu 26.04 LTS
- Kali Linux
- Hydra (attack simulation)

## Setup
Full setup write-up: [01-setup.md](./01-setup.md)

Deployed Wazuh's Manager, Indexer, and Dashboard components using Docker
Compose rather than a manual installation, for a more reliable and
resource-efficient deployment — closer to how modern security teams
actually run this kind of tooling.

## Scenarios
| Scenario | Status | Summary |
|---|---|---|
| [Brute Force Detection](./scenario-1-bruteforce.md) | In progress | Simulated SSH/login brute-force attack from Kali, detected via Wazuh dashboard |
| Manual Log Analysis | Planned | Investigating Windows/Linux logs directly through Wazuh |
| Phishing Analysis | Planned | Analyzing a simulated phishing email using header/sender indicators |
| Playbook Response | Planned | Writing and following a self-authored incident response playbook |

## Challenges & Troubleshooting
Getting this lab running was not a smooth, single attempt — and that
process is worth documenting honestly:
- An initial manual Wazuh installation repeatedly failed due to CPU/RAM
  requirement checks, port conflicts from interrupted install attempts,
  and the Wazuh Indexer timing out on startup due to memory limits
- Diagnosed each issue individually using logs (`journalctl`,
  `/var/log/wazuh-install.log`), system resource tools (`free -h`,
  `nproc`, `df -h`), and process inspection (`lsof`)
- After repeated failures, pivoted to a Docker-based deployment —
  a more modern, resource-efficient, and production-realistic approach
- Hit a full-disk failure mid-deployment (0 bytes free), resized the
  virtual disk from 21GB to 40GB, and when the VM became unstable
  afterward, rebuilt it cleanly with correctly-sized resources from the
  start
- The second build completed successfully end-to-end

## Skills Demonstrated
- SIEM deployment and configuration (Wazuh)
- Docker-based infrastructure deployment
- Independent troubleshooting of real infrastructure issues (resource
  limits, port conflicts, disk management, VM recovery)
- Alert monitoring and severity assessment
- Log analysis (planned scenarios)
- Incident documentation and reporting
