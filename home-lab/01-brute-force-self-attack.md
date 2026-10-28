## What I did
Ran a real brute-force attack against this VM's own SSH service (Hydra
targeting 127.0.0.1), after installing the Wazuh Agent on the host itself
so it could forward real system logs to the Dockerized Wazuh Manager.

## What I learned
A Wazuh Manager running in Docker cannot see the host machine's own logs
by default - it only sees activity inside its own container. Installing
the Wazuh Agent directly on the host (Kali) and pointing it at the local
manager (127.0.0.1) is what actually connects the two, letting real
system activity (like SSH login attempts) reach the SIEM.

## What I found
Wazuh detected the brute-force attempt and automatically classified it
under MITRE ATT&CK's "Password Guessing" technique. The dashboard showed
1 alert, correctly timestamped to match the exact moment Hydra ran, with
the "kali" agent correctly identified as the source of the activity.

## Why this matters
This is the complete detection loop working end to end: attack happens,
agent forwards the log, manager analyzes and classifies it, analyst (me)
reviews the result on the dashboard. Diagnosing why the first attack
attempt produced no alert - and fixing it by understanding how Docker
containers and host-level agents relate - is a real troubleshooting skill,
not just following a guide.  

![Wazuh MITRE detection](./Screenshot%202026-10-27%20161457.png)
