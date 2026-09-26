## What I did
Completed the Linux Threat Detection 2 room on TryHackMe.

## What I learned
Learned about "Hack and Forget" attacks on Linux - tracing the full attack
lifecycle from initial Discovery commands through to final Impact - and
practiced detecting these stages using auditd and authentication logs,
including uncovering an actual cryptominer attack.

## What clicked
This mirrors the Cyber Kill Chain structure directly - Discovery through
Impact matches the kill chain's stages, and seeing a real cryptominer
attack traced end-to-end through auditd/auth logs made that framework
concrete on Linux, similar to how Windows Threat Detection 2 did with
Sysmon for privilege escalation.

## Why this matters
Cryptominer attacks are a common real-world "hack and forget" scenario -
attackers install mining malware and leave it running for profit. Being
able to trace the full lifecycle using audit logs ties together the Cyber
Kill Chain framework with practical Linux log analysis in one complete
investigation.
