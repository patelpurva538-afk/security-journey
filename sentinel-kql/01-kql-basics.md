## What I did
Completed the "Construct KQL statements for Microsoft Sentinel" module
(part of Microsoft's free SC-200 course on Microsoft Learn).

## What I learned
Learned the basic building blocks of a KQL statement: search, where, let,
extend, order by, project, and project-away.

## What clicked
The where operator filters down to specific events - for example, finding
only events with ID 4628, or only failed or successful login attempts. The
project operator controls which columns actually show up in the results,
so you see only the fields that matter instead of everything in the table.

## Why this matters
This is directly comparable to SQL's WHERE and SELECT from Pre Security's
Database SQL Basics room - KQL is doing the same core job (filter rows,
choose columns) but for Microsoft's cloud security data instead of a
general database. Understanding this parallel makes KQL feel like a new
syntax for a skill already built, not something totally unfamiliar.
