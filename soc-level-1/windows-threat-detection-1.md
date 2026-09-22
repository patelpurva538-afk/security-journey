## What I did
Completed the Windows Threat Detection 1 room on TryHackMe.

## What I learned
Learned to detect specific attacker techniques on Windows systems - covering
USB-based attacks, malware behavior, and phishing-related activity, using
specific Event IDs to identify these threats.

## What clicked
This directly applies the Event Viewer/Event ID knowledge from Windows
Logging for SOC - instead of just knowing where logs live, this room showed
which specific Event IDs to look for when investigating particular threat
types like USB attacks or phishing-related malware execution.

## Why this matters
This connects several earlier concepts together - Systems as Attack Vectors
covered USB Rubber Ducky-style attacks in theory, and now this room shows
the actual Windows Event IDs that would reveal such an attack happened,
turning an earlier abstract concept into a concrete detection skill.
