## What I did
Completed the Become a Hacker room on TryHackMe.

## What I learned
Practiced an attacker's workflow end-to-end - using gobuster and dirbuster
with a password list to find hidden directories, then using a weak password
found through this process to log into an admin panel on a practice website.

## What clicked
This tied directly back to Offensive Security Intro from the very start of
Pre Security - same core technique (directory enumeration + weak
credentials), but now understood more deeply after learning HTTP, web
mechanics, and password security in between. What felt like a magic trick at
the start now makes clear technical sense.

## Why this matters for security
Understanding this exact attacker workflow - enumeration, then exploiting
weak credentials - is essential for blue team work too, because you can't
defend against a technique you don't understand. Recognizing gobuster/dirbuster
traffic patterns in logs (many rapid requests to different paths) is a real
detection signal covered in the earlier Defensive Security Intro room.
