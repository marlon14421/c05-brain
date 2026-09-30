---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-692"
status: "Draft"
---
# CWE-692: Incomplete Denylist to Cross-Site Scripting

**Abstraction:** Compound  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The product uses a denylist-based protection mechanism to defend against XSS attacks, but the denylist is incomplete, allowing XSS variants to succeed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-184 (StartsWith)
- CWE-184 (ChildOf)

## Source

- [CWE-692 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/692.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
