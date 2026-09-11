## What I did
Completed the Client-Server Basics room on TryHackMe.

## What I learned
Learned how the request/response cycle works between a client (like a browser)
and a server - covering HTTP methods (like GET), the URL scheme, hostname, and
how to inspect actual web traffic to see requests and responses happening
in real time.

## What clicked
Understood that every webpage load is really a client sending a request and a
server sending back a response - and that you can actually watch this exchange
happen live using browser inspection tools, instead of it being invisible.

## Why this matters for security
This is the foundation for spotting suspicious web traffic later - a defender
needs to recognize what a normal GET request looks like in order to notice
when something abnormal shows up (unexpected requests, unusual methods, or
traffic going to suspicious hosts). This directly connects to the Network
Traffic Analysis and Phishing Analysis work coming up in SOC Level 1.
