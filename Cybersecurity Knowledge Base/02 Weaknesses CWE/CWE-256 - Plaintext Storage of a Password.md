---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-256"
status: "Incomplete"
---
# CWE-256: Plaintext Storage of a Password

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, ICS/OT

## Description

The product stores a password in plaintext within resources such as memory or files.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Avoid storing passwords in easily accessible locations.
- **Architecture and Design:** Consider storing cryptographic hashes of passwords as an alternative to storing in plaintext.
- **Mitigation:** A programmer might attempt to remedy the password management problem by obscuring the password with an encoding function, such as base 64 encoding, but this effort does not adequately protect the password because the encoding can be detected and decoded easily.

## Related weaknesses

- CWE-522 (ChildOf)

## Source

- [CWE-256 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/256.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
