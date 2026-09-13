## What I did
Completed the How Websites Work room on TryHackMe.

## What I learned
Learned how websites are built and run using JavaScript for interactivity,
and how inspecting a page's code can reveal hidden weaknesses - including how
malicious JavaScript can be injected into a page, and how inspecting/changing
code client-side can sometimes expose hidden passwords or other weaknesses.

## What clicked
Connected this directly back to earlier rooms - HTTP requests/responses, the
FakeBank admin panel exercise, and now seeing how the actual website code
(JavaScript especially) can be manipulated or inspected to find flaws, ties
the web-based attack surface together as one connected picture.

## Why this matters for security
Malicious JavaScript injection (like XSS - cross-site scripting) is one of
the most common real-world web attacks, and inspecting client-side code for
hidden secrets (like hardcoded passwords) is a genuine vulnerability class.
This is core knowledge for both understanding attacker techniques and for
defenders reviewing web application security.
