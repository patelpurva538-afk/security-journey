## What I did
Completed the What is Networking? room on TryHackMe.

## What I learned
Learned the basics of how devices communicate over a network - covering
ping, IP addresses, MAC addresses, ICMP (the protocol ping uses), and basic
command syntax for testing connectivity.

## What clicked
Understood that ping isn't just a random command - it uses ICMP specifically
to test whether a device is reachable, and IP/MAC addresses are the two
different ways a device is identified (IP for logical network addressing,
MAC for the physical hardware).

## Why this matters for security
Ping and ICMP traffic are things a SOC analyst monitors - unusual ping sweeps
across a network can indicate someone scanning for live hosts before an
attack. Understanding normal IP/MAC/ICMP behavior is the baseline needed to
recognize abnormal network activity later in Network Traffic Analysis.
