---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-261"
status: "Incomplete"
---
# CWE-261: Weak Encoding for Password

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

Obscuring a password with a trivial encoding does not protect the password.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Mitigation:** Passwords should be encrypted with keys that are at least 128 bits in length for adequate security.

## Related weaknesses

- CWE-522 (ChildOf)

## Source

- [CWE-261 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/261.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
