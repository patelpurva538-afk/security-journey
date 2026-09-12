## What I did
Completed the Data Encoding room on TryHackMe.

## What I learned
Learned about ASCII and its limitations (only covers a small set of English
characters), and how Unicode was created to solve this - covering the world's
languages and symbols like emojis and chess pieces. Also covered the three
main Unicode encoding standards: UTF-8, UTF-16, and UTF-32.

## What clicked
Understood why Unicode had to exist at all - ASCII simply couldn't represent
most of the world's writing systems, so a much larger, flexible standard was
needed, with UTF-8 being the most common because it's efficient for common
characters while still supporting everything else.

## Why this matters for security
Encoding differences matter in security because attackers sometimes use
encoding tricks (like unusual Unicode characters or encoding payloads
differently) to slip malicious input past filters that only check for plain
ASCII patterns - this connects to how log analysis and input validation need
to account for more than just simple text matching.
