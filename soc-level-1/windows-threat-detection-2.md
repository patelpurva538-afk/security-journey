## What I did
Completed the Windows Threat Detection 2 room on TryHackMe.

## What I learned
Went deeper than Part 1 - covering privilege escalation-related Event IDs,
using Sysmon logs (a more detailed Windows logging tool) to trace file
patterns, and identifying trojan-related activity.

## What clicked
Sysmon logs gave a much more detailed view than standard Windows Event
Viewer logs from the previous room - this showed why dedicated logging
tools exist beyond built-in OS logs, since Sysmon captures more granular
detail needed to trace something like privilege escalation or a trojan's
file activity.

## Why this matters
Privilege escalation is a specific MITRE ATT&CK tactic - being able to spot
it via Sysmon logs connects the theoretical framework from the MITRE room
to an actual practical detection method, showing progression from Windows
Threat Detection 1's basics into deeper, tool-assisted investigation.
