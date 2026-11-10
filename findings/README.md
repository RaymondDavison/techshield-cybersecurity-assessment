# Vulnerability register

Scores retain their provenance. Scanner labels and CVSS versions must not be conflated. Critical/High priorities appear first, with infrastructure scanner observations following validated attack paths.

| Finding | Severity and score |
|---|---|
| [MS17-010 SMB remote code execution](01-ms17-010.md) | High; scanner-reported 8.1. Source reports also claim 10.0 and 8.8, which are not adopted as a unified score. |
| [Executable file upload in DVWA](02-upload-rce.md) | Critical qualitative lab risk; numerical CVSS unassigned. |
| [SQL injection in DVWA](03-sql-injection.md) | High qualitative lab risk; numerical CVSS unassigned. |
| [Stored XSS in DVWA](04-stored-xss.md) | High source qualitative rating; numerical CVSS unassigned. |
| [Weak local credentials and password reuse](05-weak-credentials.md) | Source-derived CVSS v3.1 9.8 for online guessing; 6.7 for privileged offline extraction. These contextual ratings are retained as source assessments. |
| [Windows SMB Server NTLM multiple vulnerabilities KB971468](06-kb971468.md) | Scanner-reported 10.0; Critical under CVSS v3-style bands; source version/vector unavailable. |
| [End-of-life operating system](07-eol.md) | Scanner-reported 10.0; Critical under CVSS v3-style bands; source version/vector unavailable. |
| [DCE/RPC and MSRPC enumeration](08-rpc.md) | Scanner-reported 5.0 Medium; version/vector unavailable. |
| [TCP timestamps enabled](09-timestamps.md) | Scanner-reported 2.6 Low; version/vector unavailable. |

CVSS v3.1 qualitative ranges are None 0.0, Low 0.1–3.9, Medium 4.0–6.9, High 7.0–8.9 and Critical 9.0–10.0. Unknown scanner versions remain explicitly unknown. No new scores were calculated. KB4013389 is represented within MS17-010 to avoid double counting.
