## What I did
Completed the Network Discovery Detection room on TryHackMe.

## What I learned
Used Elastic (the SIEM tool from earlier) to identify a port sweep attack -
detecting when someone is scanning across multiple ports on a network to
discover open services, a network-level version of the discovery/enumeration
concept.

## What clicked
This connects directly back to the FakeBank dirbuster exercise from Pre
Security - that was directory enumeration at the web/application level,
while a port sweep is the same underlying idea (systematically probing for
weaknesses) but at the network level, and now using Elastic to detect it
rather than just reading about detection in theory.

## Why this matters
Port sweeps are often an early reconnaissance step before a real attack
(matching the first stage of the Cyber Kill Chain), so detecting one early
in Elastic gives a defender a chance to respond before an attacker finds
and exploits an actual vulnerability.
