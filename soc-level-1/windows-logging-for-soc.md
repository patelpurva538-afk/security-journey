## What I did
Completed the Windows Logging for SOC room on TryHackMe.

## What I learned
Learned about Windows-specific logging - Event Viewer, Security logs, and
specific Event IDs used to track things like login attempts, process
creation, and other security-relevant activity on a Windows system.

## What clicked
This built directly on Windows Basics and Windows CLI Basics from Pre
Security - those rooms introduced navigating Windows and its command line,
and this room showed exactly where the security-relevant data lives (Event
Viewer, Security logs) and how to read it for investigation purposes.

## Why this matters
Since many organizations run Windows environments, being able to read
Windows Event Logs and recognize meaningful Event IDs (like failed logins or
suspicious process creation) is just as essential as Linux log analysis for
a SOC analyst who needs to investigate incidents across different operating
systems.
