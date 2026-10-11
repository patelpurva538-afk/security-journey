## What I did
Completed "Work with data in Microsoft Sentinel using Kusto Query
Language" (part of Microsoft's free SC-200 course on Microsoft Learn).

## What I learned
Learned the parse and extract operators. Extract uses a regex pattern to
pull out one specific value from a string, while parse traces through
structured or semi-structured data to pull multiple fields out at once.

## What clicked
This is the exact same underlying skill as the regex work planned for
Python (extracting IPs from a log file) - extract in KQL does the same
job as Python's re module, just inside the query language instead of a
script. Parse goes further, handling messier or more structured log
lines in one step rather than extracting fields one at a time.

## Why this matters
Real log data is rarely clean - a raw log line often has a timestamp, IP,
username, and status all jammed into one string. Extract and parse are
what actually turn that mess into usable, filterable fields, which is
the same core skill as Pre Security's regex work and the Python log-
parsing projects, just applied to Microsoft Sentinel's query language.
