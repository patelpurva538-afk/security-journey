## What I did
Wrote a Python script that uses regex (regular expressions) to find and
extract IP addresses from a log file, instead of relying on their
position in the line like the earlier .split()[-1] approach.

## What I learned
Used Python's re module and the pattern \d+\.\d+\.\d+\.\d+ to match any
IP address structure (digits, dot, digits, dot, digits, dot, digits),
regardless of where it appears in the line. re.search() finds the match,
and match.group() extracts the actual matched text.

## What I found
The script correctly found and printed the IP address from each log
line, confirming the regex pattern worked - a more flexible approach
than assuming the IP is always the last word in a line.

## Why this matters
Real log lines aren't as predictable as a fake sample file - fields
move around, extra text gets added, formats vary between systems.
Regex-based extraction is the actual technique used in real log parsing
because it finds a pattern anywhere in messy text, rather than relying
on a fixed position that breaks the moment log formatting changes.
