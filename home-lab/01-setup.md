## What I did
Built a working Wazuh SIEM using Docker, end to end, after an earlier attempt
at a raw VM install failed repeatedly on hardware/dependency issues. Resolved
problems along the way including CPU/RAM allocation, port conflicts, a full
disk, and a corrupted VM requiring a clean rebuild.

## What I learned
Deployed Wazuh's manager, indexer, and dashboard as Docker containers using
their official docker-compose setup - a more modern, resource-efficient
deployment method than a manual install. Logged into the dashboard and saw
real alert data (46 medium, 141 low severity) generated from the system's
own activity.

## What I found
A fully functional Wazuh dashboard, running locally, showing live alert
severity breakdowns and giving access to modules for configuration
assessment, malware detection, file integrity monitoring, threat hunting,
MITRE ATT&CK mapping, and vulnerability detection.

## Why this matters
Containerized deployment (Docker) is how modern security teams actually run
tools like this, so this demonstrates current, practical deployment skill -
not just following a guided tutorial. Troubleshooting real infrastructure
problems (resource limits, port conflicts, disk space, VM corruption) and
recovering from them independently is exactly the kind of resilience and
problem-solving a Tier 1 SOC role requires.
