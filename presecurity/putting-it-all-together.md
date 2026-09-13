## What I did
Completed the Putting it all together room on TryHackMe - the capstone of
the How The Web Works section.

## What I learned
Connected everything from this section into one full picture: how a website
actually loads, from sending a request, checking DNS to resolve the domain
to an IP address, getting a response back, and how the server talks to a
database behind the scenes to serve the final page.

## What clicked
Seeing the entire flow end-to-end for the first time - DNS resolution, the
HTTP request/response cycle, and database interaction all happening in
sequence for something as simple as loading one webpage - made all the
separate rooms (DNS in Detail, HTTP in Detail, SQL Basics, Client-Server
Basics) click together as one connected system instead of isolated topics.

## Why this matters for security
Understanding this full flow is exactly what's needed to spot where an
attack can happen at each stage - DNS spoofing at the resolution step, a
malicious request at the HTTP step, or SQL injection at the database step.
Knowing the normal end-to-end flow is the baseline for recognizing where and
how it's being abused.
