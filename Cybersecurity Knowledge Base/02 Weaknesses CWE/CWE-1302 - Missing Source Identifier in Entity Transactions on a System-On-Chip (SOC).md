---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1302"
status: "Incomplete"
---
# CWE-1302: Missing Source Identifier in Entity Transactions on a System-On-Chip (SOC)

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product implements a security identifier mechanism to differentiate what actions are allowed or disallowed when a transaction originates from an entity. A transaction is sent without a security identifier.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Transaction details must be reviewed for design inconsistency and common weaknesses.
- **Implementation:** Security identifier definition and programming flow must be tested in pre-silicon and post-silicon testing.

## Related weaknesses

- CWE-1294 (ChildOf)

## Source

- [CWE-1302 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1302.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
