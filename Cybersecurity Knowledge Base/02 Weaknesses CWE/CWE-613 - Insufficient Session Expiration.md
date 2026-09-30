---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-613"
status: "Incomplete"
---
# CWE-613: Insufficient Session Expiration

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

According to WASC, "Insufficient Session Expiration is when a web site permits an attacker to reuse old session credentials or session IDs for authorization."

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Set sessions/credentials expiration date.

## Related weaknesses

- CWE-672 (ChildOf)
- CWE-672 (ChildOf)
- CWE-287 (CanPrecede)

## Source

- [CWE-613 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/613.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
