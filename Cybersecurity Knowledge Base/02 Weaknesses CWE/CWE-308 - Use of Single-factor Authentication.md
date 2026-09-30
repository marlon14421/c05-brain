---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-308"
status: "Draft"
---
# CWE-308: Use of Single-factor Authentication

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product uses an authentication algorithm that uses a single factor (e.g., a password) in a security context that should require more than one factor.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use multiple independent authentication schemes, which ensures that -- if one of the methods is compromised -- the system itself is still likely safe from compromise. For this reason, if multiple schemes are possible, they should be implemented and required -- especially if they are easy to use.

## Related weaknesses

- CWE-1390 (ChildOf)
- CWE-654 (ChildOf)
- CWE-309 (PeerOf)

## Source

- [CWE-308 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/308.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
