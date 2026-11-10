# Source review and publication boundaries

The source collection comprises 17 Word documents, six PDF reports and one slide deck. Multiple drafts repeat the same evidence. Embedded images were extracted and reviewed as a collection. PDF text was extracted to compare narrative claims. No standalone scanner XML, raw Nmap output, forensic disk image or recovered JPEG binaries were present.

The capstone statement supplies the lab context. Separate evaluation parameters, VAPT template and reference report were absent. This portfolio therefore uses the eight-part format specified in the project request. Academic reports and instructional graphics are excluded from publication.

## Corrections and unresolved questions

- Greenbone credentials are configured, but no authentication-success result is visible. Authenticated coverage remains unverified, including any claim of patch-level local checks.
- Netdiscover range mode is active discovery. The report's passive label is corrected.
- The source gives MS17-010 scores of 10.0, 8.1 and 8.8. The 8.8 vector assumes prior low privileges while the narrative describes unauthenticated exploitation. The scanner row's 8.1 is preserved with attribution. No universal replacement score is invented.
- A screenshot's Nmap CVE identifier does not prove each CVE in an MS17-010 exploit family independently.
- Linux service banners establish exposed legacy services. They do not prove every known vulnerability associated with those versions.
- SYSTEM access is supported on Windows. DVWA command execution is supported at the web service identity. Additional privilege escalation and lateral movement remain unproven.
- Credential narratives contain inconsistent values. Public documentation omits all values and retains only the supported security outcome.
- Some source captions are placeholders. A caption alone is not evidence that its proposed action occurred.

## Sandbox lifecycle and publication context

The project owner confirms that the authorized training sandbox has been destroyed. The retained private addresses, generic lab identities and exploit output describe that historical environment. Credential values remain omitted from this edition as a reporting choice. Their omission does not imply that the destroyed sandbox remains accessible.

## Sanitization and provenance

Original files remain outside this repository. A separate private archive contains unchanged originals and SHA-256 inventory. The public package contains authored Markdown, selected screenshots and a screenshot manifest. Office/PDF metadata, comments, embedded packages and instructor materials are excluded by excluding their source containers entirely.

Selected screenshots were reviewed for credentials, account tokens, hashes and personal information. Images containing those elements were omitted. Included images were re-encoded to remove metadata without changing their technical pixels. The public manifest records source-image and output hashes. Generic lab identities and RFC1918 addresses remain intentionally visible.

Raw XML sanitization could not be performed because no scanner XML was supplied. No simulated XML or fabricated tool output is included. Review this package before publication.
