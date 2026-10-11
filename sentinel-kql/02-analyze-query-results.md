## What I did
Completed "Analyze query results using KQL" (part of Microsoft's free
SC-200 course on Microsoft Learn).

## What I learned
Learned the summarize operator, which condenses and groups specific data
out of a full dataset instead of looking at every raw row. Also learned
the render operator, which turns query results into visualizations -
bar charts, pie charts, and time charts.

## What clicked
Summarize is the KQL equivalent of answering a question like "how many
failed logins per IP" rather than scrolling through every single log line
- and render takes that summarized data and turns it into something visual,
which is exactly how a SOC dashboard shows trends at a glance instead of
raw numbers.

## Why this matters
This connects directly to the Wazuh dashboard and the Alert Triage With
Splunk/Elastic work from SOC Level 1 - every SIEM needs a way to
summarize raw logs into meaningful patterns and display them visually.
KQL's summarize and render do in Microsoft Sentinel what Splunk and
Elastic's own query/visualization tools do in those platforms - same
underlying skill, different syntax.
