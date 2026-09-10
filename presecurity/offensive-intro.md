## What I did
Completed the Offensive Security Intro room on TryHackMe. Used dirbuster to scan
the FakeBank practice website for hidden pages and found an admin panel.

## What I learned
Learned that websites can have hidden pages (like admin panels) that aren't linked
anywhere visible, and tools like dirbuster can find them by trying thousands of
common page names automatically.

## What I found
The admin page gave access to different accounts and let me add money to them
without proper authorization - a weak/broken access control issue.

## Why this matters
On a real website, if an attacker finds an admin page like this, they could misuse
it to move money illegally. This is exactly the kind of flaw defenders (blue team)
need to catch and fix before attackers find it.
