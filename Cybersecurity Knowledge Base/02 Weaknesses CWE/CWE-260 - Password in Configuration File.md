---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-260"
status: "Incomplete"
---
# CWE-260: Password in Configuration File

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product stores a password in a configuration file that might be accessible to actors who do not know the password.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Avoid storing passwords in easily accessible locations.
- **Architecture and Design:** Consider storing cryptographic hashes of passwords as an alternative to storing in plaintext.

## Related weaknesses

- CWE-522 (ChildOf)

## Source

- [CWE-260 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/260.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
