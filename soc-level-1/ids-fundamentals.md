## What I did
Completed the IDS Fundamentals room on TryHackMe.

## What I learned
Learned about IDS (Intrusion Detection System) types - network-based (NIDS)
vs host-based (HIDS), and signature-based (matching known attack patterns)
vs anomaly-based (flagging unusual behavior compared to a baseline)
detection approaches.

## What clicked
Understood how IDS fits alongside EDR and SIEM from earlier - EDR focuses on
endpoint telemetry, SIEM centralizes and correlates logs, and IDS
specifically watches for intrusion patterns, either at the network level
(NIDS) or on an individual host (HIDS), using either known signatures or
behavioral anomalies.

## Why this matters
Knowing IDS types explains why some attacks bypass certain defenses -
signature-based detection only catches known threats, while a novel or
disguised attack (like a modified hash from the Pyramid of Pain lesson)
might slip past signature-based IDS but get caught by anomaly-based
detection instead. This directly ties multiple earlier frameworks together.
