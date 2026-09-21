## What I did
Completed the Web Security Essentials room on TryHackMe.

## What I learned
Reinforced how websites work while covering web-specific defenses - CDNs
(Content Delivery Networks), WAFs (Web Application Firewalls), signature-
based protection, and system hardening techniques to limit attack surface.

## What clicked
This built on How Websites Work and the FakeBank dirbuster exercise from
Pre Security by adding the defensive layer - a WAF is specifically designed
to catch the kind of enumeration/exploitation attempts (like dirbuster
scanning or the admin panel exploit) at the web application level, similar
to how Snort does it at the network level.

## Why this matters
Web applications are one of the most common attack surfaces (as shown
repeatedly through the FakeBank exercises), so understanding WAFs and
hardening techniques closes the loop on defending exactly the kind of
vulnerability found and exploited earlier in Pre Security.
