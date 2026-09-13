## What I did
Completed the Packets & Frames room on TryHackMe.

## What I learned
Learned about TCP vs UDP, different types of ports, and how packets and
frames actually work as data moves across a network.

## What clicked
Connected this back to the OSI model - frames operate at a lower layer
(Layer 2) while packets operate at a higher layer (Layer 3), and TCP/UDP sit
above that, using ports to direct traffic to the right application on a
device.

## Why this matters for security
Ports and protocols (TCP vs UDP) are exactly what shows up in packet captures
and firewall rules - knowing which ports are normally open for which services
is what lets a defender spot something abnormal, like traffic on an unusual
port that could indicate malware communicating with an attacker. This is
directly needed for the Wireshark practice and Network Traffic Analysis work
coming up.
