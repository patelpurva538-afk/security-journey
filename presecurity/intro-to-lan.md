## What I did
Completed the Intro to LAN room on TryHackMe.

## What I learned
Learned about ARP (matching IP to MAC addresses), DHCP (automatically
assigning IP addresses to devices), different network topologies, common
connection flaws/failure points, and subnetting - including how IP addresses
are broken down into octets.

## What clicked
Understood how ARP and DHCP work together behind the scenes every time a
device joins a network - DHCP assigns it an IP, and ARP figures out which
physical device (MAC address) matches which IP when devices communicate.

## Why this matters for security
ARP and DHCP are both commonly abused in real attacks - ARP spoofing lets an
attacker intercept traffic by lying about IP-to-MAC mappings, and rogue DHCP
servers can hand out malicious network settings. Understanding how these
protocols are supposed to work is what lets a defender recognize when they've
been tampered with, which connects directly to Network Traffic Analysis in
SOC Level 1.
