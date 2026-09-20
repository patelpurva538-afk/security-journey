## What I did
Completed the Man in the Middle Detection room on TryHackMe.

## What I learned
Learned how to detect three types of MITM attacks: ARP spoofing (found by
checking for duplicate MAC addresses tied to different IPs using arp -a or
spotting it in Wireshark), DNS spoofing (found by identifying multiple,
conflicting DNS responses), and SSL stripping (exposed by finding sensitive
data like passwords sent in plaintext over HTTP instead of HTTPS).

## What clicked
This ties together several earlier rooms directly - ARP from Intro to LAN
(now seeing exactly how it's abused and detected), DNS from DNS in Detail
(now seeing spoofing detection specifically), and encryption from
Cryptography Concepts (SSL stripping is essentially forcing a downgrade
from encrypted to plaintext communication).

## Why this matters
MITM attacks are dangerous specifically because they're invisible to the
victim unless someone is actively monitoring for these exact signs -
knowing the specific indicator for each type (duplicate MACs, conflicting
DNS responses, unexpected plaintext HTTP) turns an abstract threat into a
concrete, checkable pattern during an investigation.
