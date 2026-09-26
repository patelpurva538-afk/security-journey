## What I did
Completed the Linux Threat Detection 1 room on TryHackMe.

## What I learned
Learned to detect phishing-related activity and suspicious SSH access on
Linux systems, using grep to search relevant logs for signs of compromise.

## What clicked
This mirrors Windows Threat Detection 1's structure directly - same starting
point (phishing detection) but adapted to Linux-specific access methods like
SSH instead of Windows-specific ones, reinforcing the pattern that most
threat categories appear on both operating systems, just with different
technical footprints.

## Why this matters
SSH is one of the most commonly targeted services on Linux systems (brute
forcing, unauthorized access), so being able to grep through logs for
suspicious SSH activity is a practical, frequently-needed skill, directly
building on the Linux Logging for SOC room just completed.
