## What I did
Completed the Phishing Emails in Action room on TryHackMe.

## What I learned
Applied the phishing analysis fundamentals to real/simulated samples,
learning specifically how malicious .exe attachments are used in phishing,
and how BCC (Blind Carbon Copy) can be abused to send phishing emails to
many recipients without them seeing each other.

## What clicked
Seeing the sender/links/attachments/headers checklist from the fundamentals
room actually applied to a real example made the process concrete - spotting
a suspicious .exe attachment or unusual BCC usage isn't abstract anymore,
it's a specific thing to check for every time.

## Why this matters
.exe attachments are one of the most common malware delivery methods via
email, and understanding BCC abuse explains how attackers scale phishing
campaigns to hit many targets at once while looking like a single email.
This is exactly the kind of real judgment call a Tier 1 analyst makes daily
when triaging a reported phishing email.
