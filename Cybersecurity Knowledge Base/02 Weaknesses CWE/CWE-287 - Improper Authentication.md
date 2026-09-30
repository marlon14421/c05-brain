---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-287"
status: "Draft"
---
# CWE-287: Improper Authentication

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Technology-Specific, Web Based, ICS/OT

## Description

When an actor claims to have a given identity, the product does not prove or insufficiently proves that the claim is correct.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use an authentication framework or library such as the OWASP ESAPI Authentication feature.

## Related weaknesses

- CWE-284 (ChildOf)
- CWE-284 (ChildOf)

## Source

- [CWE-287 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/287.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
