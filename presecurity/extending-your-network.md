## What I did
Completed the Extending Your Network room on TryHackMe.

## What I learned
Learned how VPNs work, firewalls and their rules, the role of routers and
switches in network security, and how TCP establishes a connection through
its handshake process before sending data.

## What clicked
Understood the TCP handshake as the "introduction" step before real data
flows - devices confirm they're both ready to communicate before anything
is actually sent, which explains why TCP is considered more reliable than UDP.

## Why this matters for security
Firewall rules are one of the most direct defensive tools a SOC analyst
works with - deciding what traffic is allowed in/out based on port, protocol,
or source. VPNs matter for secure remote access, and understanding the TCP
handshake helps spot anomalies like incomplete handshakes, which can indicate
scanning or certain types of attacks (e.g. SYN flood).
