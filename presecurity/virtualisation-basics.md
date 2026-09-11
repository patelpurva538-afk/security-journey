## What I did
Completed the Virtualisation Basics room on TryHackMe.

## What I learned
Learned how virtualisation lets you run multiple operating systems on one
physical machine using a VM manager (hypervisor), how this saves companies
money by needing fewer physical machines, and how Docker containerization
offers a lighter alternative for the same cost-saving goal.

## What clicked
Understood why VMs are used for security testing specifically - running a
suspicious or malicious file inside a VM keeps it isolated from the real
system, so if something goes wrong, only the throwaway VM is affected, not
your actual computer.

## Why this matters for security
This is exactly why the home lab project uses VMs - it lets you safely run an
attacker machine and a target machine on one computer, isolated from your real
system and network, so you can practice detecting real attack behavior (like
brute force attempts) without any actual risk. This room directly explains the
"why" behind the home lab setup planned for later.
