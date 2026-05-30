# IDMWFP64.sys — Vulnerability Disclosure

This repository is the public anchor for a coordinated vulnerability
disclosure affecting `idmwfp64.sys`, the Windows kernel driver shipped
with Internet Download Manager (IDM) by Tonec FZE.

**Status:** CVE pending assignment from MITRE CNA-LR.
**Public disclosure target:** on or after **2026-08-27** (90-day embargo).

The full technical writeup, proof-of-concept code, and reverse-engineering
notes are currently under coordinated disclosure embargo and will be
published here when the embargo closes.

## Affected component

- **File:** `idmwfp64.sys`
- **Product:** Internet Download Manager (IDM)
- **Vendor:** Tonec FZE
- **Vulnerability class:** Incorrect Permission Assignment for Critical Resource (CWE-732), leading to local privilege escalation to NT AUTHORITY\SYSTEM from a standard user account.

## Disclosure timeline

| Date | Event |
|---|---|
| 2026-05-29 | Vendor (Tonec FZE) contacted via IDM support form |
| 2026-05-30 | CVE ID requested from MITRE CNA-LR (tracking: CAN-2026-2030787) |
| 2026-08-27 | Public disclosure target (90-day embargo end) |

## Researcher

Abdelhadi Ech-chaibi — [@ippy0kai](https://github.com/Abdelhadi963)

For coordinated disclosure inquiries, contact via the email associated
with the CVE request.
