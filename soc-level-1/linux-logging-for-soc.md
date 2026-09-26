## What I did
Completed the Linux Logging for SOC room on TryHackMe.

## What I learned
Learned to investigate Linux logs using grep to filter for specific events,
cron logs, and ausearch -k to search audit logs by key, identifying failed
vs accepted login attempts and the IPs involved.

## What clicked
This is the direct Linux counterpart to Windows Logging for SOC - same
underlying goal (finding failed logins, suspicious events) but different
tools and syntax (grep/ausearch vs Event Viewer/Event IDs), reinforcing that
being OS-agnostic in investigation skills matters since real environments
mix both.

## Why this matters
Combined with Windows Logging for SOC, this completes cross-OS log
investigation skills - a real SOC analyst can't assume every incident
happens on one OS, so being comfortable pulling failed-login and audit data
from both Windows and Linux systems is essential, well-rounded Tier 1 skill.
