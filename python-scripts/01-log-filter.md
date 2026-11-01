## What I did
Wrote my first Python script independently - a log file filter that reads
through a log file and prints only lines containing "failed", simulating
how a SOC analyst scans logs for suspicious activity.

## What I learned
Used file handling (open()), a for loop to read line by line, and an if
statement with string matching ("failed" in line) to filter results.
Also debugged a real "file not found" error myself - the script and the
terminal were running from different folders, so Python couldn't find the
log file until I navigated the terminal to the correct directory with cd.

## What I found
The script correctly filtered and printed only the failed login attempts
from a sample log file, ignoring successful logins - proof the core
filtering logic works.

## Why this matters
This is the exact pattern real SOC log analysis scripts use - reading
large log files and surfacing only the relevant/suspicious lines instead
of manually scanning everything. Debugging the folder-path error
independently (understanding why it failed, not just fixing it blindly)
is itself a real, transferable skill.

![Log filter output](./Screenshot%202026-11-01%20081656.png)
