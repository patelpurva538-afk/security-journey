## What I did
Completed the HTTP in Detail room on TryHackMe.

## What I learned
Went deeper into HTTP than Client-Server Basics - covering different request
methods (GET, POST, PUT, DELETE), how cookies are set via headers, and how
headers work more broadly in a request/response cycle.

## What clicked
Understood that HTTP methods aren't interchangeable - GET retrieves data,
POST sends new data, PUT updates, DELETE removes - and cookies set via
headers are how a website "remembers" a user across requests, like staying
logged in.

## Why this matters for security
Unusual HTTP methods (like DELETE or PUT hitting an endpoint that shouldn't
allow them) or suspicious cookie/header manipulation are common signs of an
attack attempt - this connects directly to the dirbuster/admin-panel exercise
from Offensive Security Intro, where finding the right method and endpoint
combination was exactly how the "admin access" vulnerability worked.
