## What I did
Completed the Living Off The Land Attacks room on TryHackMe.

## What I learned
Learned about "Living Off The Land" (LOTL) attacks - where attackers abuse
legitimate, built-in system tools like PowerShell, WMIC, Certutil, Mshta,
Rundll32, and Scheduled Tasks to carry out malicious actions instead of
using obvious external malware.

## What clicked
Understood why these attacks are especially dangerous - since these are all
legitimate, commonly-used Windows tools, signature-based detection (from IDS
Fundamentals) often can't flag them as malicious on their own, since the
tool itself isn't inherently bad - only how and why it's being used matters.

## Why this matters
This is exactly why anomaly-based detection and behavioral analysis (from
IDS Fundamentals and EDR) matter so much - a LOTL attack won't trigger a
simple "known bad file" signature, so recognizing unusual USE of a normal
tool (e.g. certutil downloading a file, an unusual purpose for that
command) is what actually catches these attacks.
