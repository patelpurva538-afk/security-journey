## What I did
Completed the Data Exfiltration Detection room on TryHackMe.

## What I learned
Learned how data exfiltration can happen through unexpected channels - DNS,
ICMP, and HTTP traffic can all be abused to sneak data out of a network -
and used Wireshark filters to identify these patterns.

## What clicked
This connects directly back to DNS in Detail from Pre Security, where TXT
records and DNS abuse for data exfiltration were mentioned - now seeing it
practically detected in Wireshark makes that earlier warning concrete. Same
with ICMP - a protocol that seemed simple in "What is Networking?" (just
ping) can actually be abused to carry hidden data out of a network.

## Why this matters
Exfiltration detection is a critical defensive skill - attackers often use
normal-looking protocols (DNS, ICMP, HTTP) specifically because they blend
in with regular traffic, so recognizing the subtle signs of abuse (like
unusual DNS query patterns) is far more valuable than just blocking obvious
malicious traffic.
