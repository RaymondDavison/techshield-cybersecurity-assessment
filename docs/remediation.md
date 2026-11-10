# Risk, remediation and lessons

## Remediation priorities

| Priority | Action | Verification |
|---|---|---|
| Immediate | Isolate exposed SMB and executable upload paths | Confirm reachability restrictions and execution denial |
| Immediate | Remediate MS17-010 and rotate exposed lab credentials | Check patch inventory, repeat detection and test authorized authentication |
| High | Replace legacy Windows and reduce unnecessary Linux services | Validate supported builds and compare service inventory |
| High | Parameterize SQL and encode browser output | Repeat documented tests and inspect application responses |
| High | Establish successful authenticated assessment coverage | Inspect authentication diagnostics and local-check execution |
| Routine | Review RPC exposure, timestamp behavior and monitoring | Retest from relevant network positions |

These are recommended actions. The provided evidence does not establish remediation deployment or successful retesting.

## Lessons and challenges

A scanner credential object establishes configuration, while successful authentication requires result-level verification. Evidence collection should include authentication diagnostics and raw exports alongside screenshots.

The original reports use different scores for the same vulnerability family. Recording CVSS version, vector and provenance at collection time prevents misleading comparisons.

The source includes a console startup fault and subsequent functioning Metasploit sessions. The exact repair is undocumented. Successful later sessions support continued testing but do not explain how the fault was resolved.

Credential and cookie screenshots are useful privately but require careful publication handling. Future evidence capture should avoid displaying secrets and should record timestamps, tool versions and hashes from the start.

## Conclusion

The lab demonstrates how exposed legacy SMB, unsafe application input handling and executable uploads can lead to substantial compromise. The portfolio connects discovery to validated outcomes and remediation, while retaining explicit uncertainty around scanner authentication, scoring provenance and unavailable raw evidence.
