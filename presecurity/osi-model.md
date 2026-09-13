## What I did
Completed the OSI Model room on TryHackMe.

## What I learned
Learned about the OSI model and its different layers, and how specific
protocols map onto them - DNS, TCP, UDP, HTTP, and OSPF each operate at a
particular layer of the model.

## What clicked
Understood that the OSI model isn't just an abstract diagram - it's a way to
place every protocol I've already learned (HTTP from Client-Server Basics,
ARP/DHCP from LAN, ICMP from networking basics) into a structured framework
showing where each one operates and how they build on each other.

## Why this matters for security
The OSI model gives a shared vocabulary for describing where an attack or
anomaly is happening - e.g. an ARP spoofing attack is a Layer 2 issue, while
a phishing site exploits Layer 7 (application layer, HTTP). This framework is
what SOC analysts use to communicate precisely about incidents during Network
Traffic Analysis and investigations.
