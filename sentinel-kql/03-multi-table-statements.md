## What I did
Completed "Build multi-table statements using KQL" (part of Microsoft's
free SC-200 course on Microsoft Learn).

## What I learned
Learned how to combine data across more than one table in KQL using
union and join.

## What clicked
Union stacks or merges all rows from two or more tables - putting them
together vertically, like combining two lists into one. Join correlates
and merges rows from two tables side-by-side based on a matching field -
more like connecting related information horizontally rather than just
stacking it.

## Why this matters
This is directly useful for real investigations - for example, joining a
table of login events with a separate threat-intel table of known
malicious IPs would let an analyst instantly see which login attempts came
from a flagged address, instead of manually cross-checking two separate
lists. This is the same kind of correlation Wazuh and Splunk do internally
when enriching an alert with threat intelligence.
