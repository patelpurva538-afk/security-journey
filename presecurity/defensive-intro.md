## What I did
Completed the Defensive Security Intro room on TryHackMe. Used a monitoring
dashboard to detect a suspicious IP making multiple access attempts on FakeBank.

## What I learned
Learned how a SOC (Security Operations Center) dashboard flags suspicious IPs
based on patterns like multiple rapid attempts to access the same page - in this
case, the admin page.

## What I found
The dashboard showed the suspicious IP clearly flagged due to repeated attempts.
Entered the IP into the dashboard and blocked it with one click.

## Why this matters
After blocking, the IP could no longer access the bank admin page it was
repeatedly targeting. This shows the core defender loop: monitor logs, spot the
anomaly (multiple attempts = suspicious), and block before real damage happens.
This is exactly what a SOC analyst does daily to stop attacks before loss occurs.
