## What I did
Completed the Database SQL Basics room on TryHackMe.

## What I learned
Learned core SQL queries: SELECT (choose what data to display), FROM (choose
the data source table), WHERE (filter records by condition), and ORDER BY
(sort results).

## What clicked
Understood SQL as a way of asking specific questions of a large dataset -
e.g. "show me only the records where X is true, sorted by Y" - rather than
manually scrolling through everything.

## Why this matters for security
SIEM tools and log databases are often queried using SQL-like syntax to pull
specific alerts or events - e.g. WHERE failed_attempts > 5, sorted by time.
This is a direct, practical skill for the SIEM Triage module coming up in
SOC Level 1, and ties in with the Python scripting projects planned that
combine SQL queries with log analysis.
