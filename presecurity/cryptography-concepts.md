## What I did
Completed the Cryptography Concepts room on TryHackMe.

## What I learned
Learned about symmetric vs asymmetric encryption, hashing algorithms,
public/private key pairs, and got hands-on with cipher tools (like Caesar
cipher-style exercises) to understand basic encryption/decryption.

## What clicked
Understood the key difference between symmetric (one shared key for both
encrypting and decrypting) and asymmetric (a public key to encrypt, a private
key to decrypt) - and that hashing is different from both since it's one-way
and used for verifying integrity, not for reverse-decrypting data.

## Why this matters for security
Encryption and hashing show up everywhere in real security work - HTTPS uses
asymmetric encryption to set up a secure connection, passwords are stored as
hashes (not plain text) so a breach doesn't expose actual passwords, and file
integrity checks use hashing to detect if a file has been tampered with. This
connects directly to the CIA Triad's Confidentiality and Integrity principles
from the last room.
