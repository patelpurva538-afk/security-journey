# Playbook: Brute-Force SSH Alert Response

A step-by-step response process I'd follow for a brute-force SSH alert,
based on my own lab investigation and SOC Level 1 training.

## Steps

1. **Initial investigation** - Check the alert's source IP, timestamp,
   targeted username, rule triggered, and severity level.

2. **Determine true vs false positive** - Look for multiple failed login
   attempts from the same IP in a short window, and check if the IP looks
   suspicious (unknown, external, or matches known bad-actor patterns).
   A single failed attempt from a known/internal IP is likely a mistyped
   password; repeated rapid attempts from an unfamiliar IP point to a
   real attack.

3. **Investigate intent** - Check what the attacker was trying to access
   - sensitive data, an attempt to upload malicious files, or something
   else - to understand the scope and risk of the attempt.

4. **Contain and escalate** - If confirmed malicious: block the source
   IP to stop further attempts. If the incident is complex or beyond
   Tier 1 scope, escalate to a Tier 2 analyst with full context.

5. **Document using the Five W's** - Record who, what, when, where, and
   why: how many attempts were made, what was targeted, the full
   timeline, and why it was judged malicious - so the next analyst (or
   Tier 2) can pick up the case without re-investigating from scratch.
