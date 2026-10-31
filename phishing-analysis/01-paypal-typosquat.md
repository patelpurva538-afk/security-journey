## What I did
Analyzed a sample phishing email impersonating PayPal, applying the
sender/link/urgency checklist from SOC Level 1's Phishing Analysis module.

## What I found

**Sender address:** `IT-Support@secure-paypa1.com` - the domain uses
"paypa1" with the numeral 1 in place of the letter "l," a classic
typosquatting technique designed to look correct at a glance.

**The link:** `http://paypal-verify-account.secure-login-update.com/verify`
- this is not a PayPal domain at all. The real domain is
"secure-login-update.com" dressed up with "paypal-verify-account" as a
subdomain prefix to look legitimate. Real PayPal links go to paypal.com
directly, not a long, unrelated domain with "paypal" stuffed into the
front.

**Urgency tactics:** the email uses "Urgent," "immediately," and a 24-hour
threat of "permanent account closure" - classic pressure language
designed to make the recipient act before thinking carefully, rather
than pause and verify.

## Verdict
This is phishing. As an analyst, I would: not click the link, report the
email as phishing, block the sender domain, and if this reached multiple
users, send a warning notice to staff not to click similar emails.

## Why this matters
Typosquatted domains (like "paypa1" instead of "paypal") and look-alike
URLs are one of the most common real-world phishing techniques, because
they rely on a quick glance rather than careful reading. Catching the
character substitution and recognizing the mismatch between the sender's
claimed identity and actual domain is the core skill behind real phishing
triage.
