# Troubleshooting: Website Will Not Load (DNS Basics)

**Status:** Draft — research and test carefully before marking this guide complete.

## What DNS does
DNS helps translate a domain name, such as `example.com`, into an IP address that computers use to connect to services.

## Diagnostic steps
1. Check whether other websites work.
2. Check whether the same website works on another device or network.
3. Confirm the domain name is typed correctly.
4. Check whether the issue is limited to one browser or app.
5. On a Windows computer, use `ipconfig /all` to view network configuration and DNS server information.
6. Use `nslookup example.com` to query DNS for a test domain. Record the output; a failed query can have several causes.
7. Compare results with another known-working network when possible.
8. Record the findings and escalate if you do not control the network.

## Notes
Use a public example domain for practice. Never publish private IP details, customer network information, or sensitive logs without permission.

## Outcome log
- Device / OS:
- Commands used:
- Output summary (remove sensitive details):
- Interpretation:
- Resolved?:
- Follow-up needed:
