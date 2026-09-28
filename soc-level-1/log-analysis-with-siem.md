## What I did
Completed the Log Analysis with SIEM room on TryHackMe.

## What I learned
Used Splunk queries to analyze different log sources inside a SIEM: Windows
logs, host-based logs, Linux logs, and web logs.

## What clicked
This pulls together several earlier rooms into one workflow. The Windows and
Linux Logging for SOC rooms showed where logs live on each OS, the Splunk
and Elastic basics rooms showed how to search, and this room applies those
searches across all the log types in one place. That is the point of a SIEM:
one search box over many different sources.

## Why this matters
Querying mixed log sources in a SIEM is the daily work of a Tier 1 analyst.
The filtering logic (choose a source, filter by condition, sort the results)
is the same thinking as SQL's SELECT, WHERE, and ORDER BY from Pre Security,
and the same thinking as the log-parsing Python scripts I plan to write.
