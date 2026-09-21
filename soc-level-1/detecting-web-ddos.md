## What I did
Completed the Detecting Web DDoS room on TryHackMe.

## What I learned
Learned to distinguish DoS (single-source) from DDoS (distributed,
multi-source) attacks, and used Splunk to query traffic by timestamp,
identifying abnormal spikes and patterns indicating an attack in progress.

## What clicked
This directly connects back to the CIA Triad from Pre Security - DDoS
attacks specifically target Availability, overwhelming a service so
legitimate users can't access it, which makes concrete something that was
only a definition back then.

## Why this matters
DDoS detection through traffic volume/timestamp analysis in Splunk is a
real, practical SOC skill, and recognizing the CIA Triad principle being
violated (Availability) helps quickly communicate the nature and severity
of an incident during reporting, connecting back to the Alert Reporting
skills from earlier in SOC Level 1.
