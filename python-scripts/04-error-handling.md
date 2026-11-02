## What I did
Combined the log-filtering script from Project 1 with try/except error
handling, so it fails gracefully with a clear message instead of
crashing if the log file doesn't exist.

## What I learned
Used try/except FileNotFoundError to wrap the file-opening and reading
logic. Tested both paths directly: renamed the log file to confirm the
script shows a friendly error message instead of crashing, then renamed
it back to confirm normal operation still works correctly.

## What I found
Both cases worked as expected - the script correctly filtered failed
login lines when the file existed, and printed a clear error message
instead of crashing when the file was renamed/missing.

## Why this matters
Real scripts run in situations you can't fully predict - a file might be
moved, deleted, or simply not exist yet when a script runs. Handling
that gracefully rather than letting the script crash with a raw Python
error is a basic but essential professional habit, and testing both the
success and failure paths (not just assuming the fix works) is itself
good practice.
