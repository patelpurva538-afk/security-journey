## What I did
Completed the IP and Domain Threat Intel room on TryHackMe.

## What I learned
Learned to check IP and domain reputation using threat intel sources,
looking at signals like DNS records and TLS certificate details to assess
whether an IP or domain is suspicious or known-malicious.

## What clicked
This connects directly to the Python project planned earlier (checking IPs
against AbuseIPDB) - this room shows the manual, conceptual version of
exactly what that script automates, and also ties back to DNS in Detail and
Cryptography Concepts (TLS/certificates) from Pre Security.

## Why this matters
Moving up the Pyramid of Pain from hashes (previous room) to IPs and
domains, this room shows a slightly more valuable indicator type - domains
and IPs are a bit harder for an attacker to change than a file hash, though
still not as durable as behavioral TTPs, reinforcing that pyramid concept
with real, checkable data points.
