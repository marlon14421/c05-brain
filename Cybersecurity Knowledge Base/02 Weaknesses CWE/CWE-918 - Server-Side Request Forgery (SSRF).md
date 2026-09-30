---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-918"
status: "Incomplete"
---
# CWE-918: Server-Side Request Forgery (SSRF)

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, AI/ML, Web Server

## Description

The web server receives a URL or similar request from an upstream component and retrieves the contents of this URL, but it does not sufficiently ensure that the request is being sent to the expected destination.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-441 (ChildOf)
- CWE-610 (ChildOf)

## Source

- [CWE-918 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/918.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
