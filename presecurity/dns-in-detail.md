## What I did
Completed the DNS in Detail room on TryHackMe.

## What I learned
Learned about different DNS record types - TXT records, MX records (mail
routing), and how DNS ultimately resolves a domain name to an IP address.

## What clicked
Understood that DNS isn't just "domain to IP" - different record types serve
different purposes, like MX records specifically directing email traffic,
while TXT records can hold arbitrary text data used for things like domain
verification.

## Why this matters for security
DNS is a common attack surface - DNS spoofing/poisoning can redirect traffic
to malicious sites, and TXT records are sometimes abused by attackers for
data exfiltration or command-and-control communication. Understanding normal
DNS record behavior is essential for spotting these abuses during Network
Traffic Analysis and Phishing Analysis in SOC Level 1.
