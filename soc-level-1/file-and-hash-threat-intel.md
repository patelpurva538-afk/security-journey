## What I did
Completed the File and Hash Threat Intel room on TryHackMe.

## What I learned
Learned to use file hashes to check against threat intelligence sources,
determining whether a file is known-malicious based on its hash value
matching existing threat intel data.

## What clicked
This directly builds on sha256sum from The Greenholt Phish and hashing from
Intro to Malware Analysis - those rooms taught how to generate a hash, and
this room completes the loop by showing what to actually do with that hash:
check it against threat intel to get a real answer about whether it's
malicious.

## Why this matters
This is also a direct real-world example of the Pyramid of Pain in action -
hash values sit at the bottom of the pyramid (easy for an attacker to
change by modifying the file slightly), so while hash-based threat intel
lookups are useful and fast, they're not foolproof, reinforcing why higher-
pyramid indicators like TTPs matter more for lasting detection.
