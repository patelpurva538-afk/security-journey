## What I did
Completed the Phishing Prevention room on TryHackMe.

## What I learned
Learned about proactive email security controls - SPF, DKIM, and DMARC
(the three main email authentication standards that verify a sender is
legitimate), and got introduced to Wireshark for packet capture analysis.

## What clicked
Understood the shift from detection to prevention - SPF/DKIM/DMARC work
before an email even reaches an inbox, verifying sender authenticity at the
infrastructure level, which is a different layer of defense than manually
checking headers after the fact like in the earlier phishing rooms.

## Why this matters
This closes the loop on the Phishing Analysis module - earlier rooms taught
how to detect and investigate phishing after it arrives, while this one
covers stopping it at the source through email authentication protocols.
The Wireshark introduction here also sets up the upcoming Network Traffic
Analysis module directly.
