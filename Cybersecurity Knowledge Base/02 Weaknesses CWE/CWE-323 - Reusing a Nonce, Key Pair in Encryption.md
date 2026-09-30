---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-323"
status: "Incomplete"
---
# CWE-323: Reusing a Nonce, Key Pair in Encryption

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

Nonces should be used for the present occasion and only once.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Refuse to reuse nonce values.
- **Implementation:** Use techniques such as requiring incrementing, time based and/or challenge response to assure uniqueness of nonces.

## Related weaknesses

- CWE-344 (ChildOf)

## Source

- [CWE-323 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/323.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
