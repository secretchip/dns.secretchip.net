---
name: False Positive Report
about: Report a legitimate domain that is incorrectly blocked
title: 'False positive: <domain>'
labels: ["false-positive"]
assignees: ''

---

## Affected domain
Domain that is being blocked:
- <example.com>

Optional subdomain or URL:
- <sub.example.com/path>

## What is happening
Describe what is blocked and how it affects you.
Include the exact error message or behavior if available.

Example:
- Website does not load.
- App cannot connect to backend.
- NXDOMAIN or 0.0.0.0 response observed.

## Expected behavior
Describe what should happen if the domain were not blocked.

## How you detected the block
Select all that apply and add details if needed:
- Browser error page
- Application error
- Router / firewall logs
- DNS query tool (dig, nslookup, etc.)
- SecretChip DNS setup verification widget

## Reproduction steps
Steps to reproduce the issue consistently:
1. Configure DNS to use SecretChip DNS.
2. Open <affected website or app>.
3. Observe failure.

## Evidence
Attach any relevant proof:
- Screenshots
- Command output (dig, nslookup)
- Error messages
- HAR files (if browser related)

## Environment
Please complete what applies:

### Desktop
- OS:
- Browser:
- Version:

### Mobile
- Device:
- OS:
- App or Browser:
- Version:

### Network
- Connection type (home, office, mobile, VPN):
- Country / ISP (optional):

## Impact
How does this affect you?
- Blocks critical work
- Minor inconvenience
- App unusable
- Other

## Additional context
Anything else that may help reproduce or diagnose the issue.
