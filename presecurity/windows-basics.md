## What I did
Completed the Windows Basics room on TryHackMe.

## What I learned
Learned how the Windows GUI works - taskbar, Start menu, running applications,
Task Manager, Windows Firewall, and built-in virus scanning. Also covered
admin vs guest account types, safe app installation through the Microsoft
Store, and how to scan specific folders and file paths for threats.

## What clicked
Understood why admin vs guest account separation exists - it limits what
damage a compromised guest account or malicious app can do, since it doesn't
have full system permissions like an admin account does.

## Why this matters for security
This is core Windows security hygiene that shows up constantly in real
incidents - Windows Firewall and built-in antivirus are often the first line
of defense, admin/guest separation limits blast radius if something goes
wrong, and knowing how to scan specific folders/paths is a basic skill for
investigating a suspected infection during incident response.
