## What I did
Completed the Tempest room on TryHackMe, a larger scenario-based
investigation.

## What I learned
Investigated an incident using log analysis and Sysmon views, identifying a
malicious file by its sha256 hash and tracing an associated IP address, then
digging deeper into the incident from there. This room was slightly harder
than earlier scenario rooms.

## What clicked
This combined several separate skills into one case: Sysmon logs from
Windows Threat Detection 2, hashing from Intro to Malware Analysis and File
and Hash Threat Intel, and IP investigation from IP and Domain Threat Intel.
Instead of practicing each one alone, I had to pull all of them together to
follow one thread from a log entry to a full picture of the incident.

## Why this matters
This is close to what a real Tier 1 to Tier 2 handoff investigation looks
like: start from a log or alert, identify a malicious artifact, pull its
hash and IP, and use threat intel to understand what you're dealing with.
It's one of the stronger capstone entries in this repo because it shows
multiple skills working together, not in isolation.
