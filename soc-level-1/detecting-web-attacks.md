## What I did
Completed the Detecting Web Attacks room on TryHackMe.

## What I learned
Learned to detect specific web attack patterns - SQL injection (SQLi) and
Cross-Site Scripting (XSS) attempts - by examining WAF logs and using
Wireshark, and distinguishing server-side versus client-side attack
indicators.

## What clicked
This closes the loop that started all the way back with the FakeBank
exercises in Pre Security - back then, exploiting the admin panel felt like
a standalone trick, but now, seeing exactly how such attacks would show up
in logs and traffic (SQLi patterns, suspicious payloads) means I can
recognize and detect the same category of attack from the defender's side.

## Why this matters
This room essentially completes the full loop from the very start of this
learning journey: Offensive Security Intro showed the attack, Defensive
Security Intro showed basic blocking, and now this room shows the detailed,
tool-based detection process a real Tier 1 analyst would use to catch SQLi
and XSS attempts before real damage occurs.
