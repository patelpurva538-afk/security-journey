## What I did
Completed the Detecting Web Shells room on TryHackMe.

## What I learned
Learned what a web shell is - malicious code planted on a server that gives
an attacker remote command execution - and how to detect one by examining
suspicious HTTP requests (unusual POST/PUT/DELETE patterns), using Wireshark
to spot the traffic, and using Linux commands like cat, grep, and whoami to
investigate a potentially compromised server.

## What clicked
This connects directly to HTTP in Detail from Pre Security - a web shell
often communicates through normal-looking HTTP methods, which is exactly
why understanding what GET/POST/PUT/DELETE should normally look like (from
that earlier room) is what makes spotting abuse of them possible now.

## Why this matters
A web shell is one of the most dangerous outcomes of a successful web
attack, since it gives an attacker ongoing remote access even after the
initial vulnerability is patched. This ties together HTTP knowledge, Linux
CLI investigation skills, and traffic analysis into one real detection
scenario - closing the loop from the original FakeBank admin panel exercise
to a full compromise-detection skill.
