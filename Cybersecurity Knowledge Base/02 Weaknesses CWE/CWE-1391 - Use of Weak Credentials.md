---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1391"
status: "Incomplete"
---
# CWE-1391: Use of Weak Credentials

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, ICS/OT, Not Technology-Specific

## Description

The product uses weak credentials (such as a default key or hard-coded password) that can be calculated, derived, reused, or guessed by an attacker.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** When the user changes or sets a password, check the password against a database of already compromised or breached passwords. These passwords are likely to be used in password guessing attacks.

## Related weaknesses

- CWE-1390 (ChildOf)

## Source

- [CWE-1391 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1391.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
