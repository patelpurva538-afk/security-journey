## What I did
Completed the Pyramid of Pain room on TryHackMe.

## What I learned
Learned about the Pyramid of Pain concept - a hierarchy of indicators from
easiest for an attacker to change (hash values at the bottom) up to hardest
to change (TTPs - Tactics, Techniques, and Procedures - at the top), and how
this connects to the MITRE ATT&CK framework's details on specific attack
behaviors.

## What clicked
Understood why it's called "pain" - blocking a hash value causes an attacker
almost no pain since they can just modify the file slightly to get a new
hash, but disrupting their actual TTPs (their real behavior and methodology)
causes real pain because it's much harder for them to change how they
fundamentally operate.

## Why this matters
This reframes what defenders should prioritize - focusing only on low-level
indicators like hashes or IPs (easy to block, easy for attackers to evade)
is less effective than understanding and disrupting TTPs. This connects
directly to threat intel lookups from earlier, showing why some indicators
are far more valuable to track than others.
