## What I did
Completed the Eviction room on TryHackMe.

## What I learned
Learned about APT28 (a known advanced persistent threat group), what their
objectives typically are, and how to identify their presence and activity
in a system as part of the eviction (removing attacker access) process.

## What clicked
Connected this directly to MITRE ATT&CK - APT28 is exactly the kind of real
threat group cataloged there, and identifying their specific TTPs is what
allows a defender to confirm eviction actually removed all their access
points, not just the most obvious one.

## Why this matters
Eviction is a critical stage of incident response - simply blocking one
indicator isn't enough if the attacker has other footholds. Understanding a
real named threat group like APT28 makes the frameworks learned earlier
(Pyramid of Pain, MITRE ATT&CK) concrete, showing how they apply to actual
known adversaries rather than just theoretical concepts.
