---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-420"
status: "Draft"
---
# CWE-420: Unprotected Alternate Channel

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product protects a primary channel, but it does not use the same level of protection for an alternate channel.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Identify all alternate channels and use the same protection mechanisms that are used for the primary channels.

## Related weaknesses

- CWE-923 (ChildOf)

## Source

- [CWE-420 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/420.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
