## What I did
Wrote a Python script that counts how many times each IP address appears
in a log file, using a dictionary to track running counts.

## What I learned
Used a dictionary (ip_counts = {}) to store IP addresses as keys and
their occurrence counts as values. The core logic - check if an IP has
been seen before, increment its count if so, otherwise start it at 1 -
mirrors how anyone naturally counts repeated items in a list by hand.

## What I found
The script correctly counted IP occurrences from the sample log file,
confirming which IP appeared most frequently - exactly the kind of check
a SOC analyst uses to spot a single source hammering a login endpoint
repeatedly.

## Why this matters
Counting occurrences by key is one of the most common patterns in real
log analysis - the same logic scales from 5 log lines to millions,
letting an analyst instantly see which IP, which user, or which event
type is happening most, without manually scanning raw logs.
