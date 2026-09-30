---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-5"
status: "Draft"
---
# CWE-5: J2EE Misconfiguration: Data Transmission Without Encryption

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

Information sent over a network can be compromised while in transit. An attacker may be able to read or modify the contents if the data are sent in plaintext or are weakly encrypted.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **System Configuration:** The product configuration should ensure that SSL or an encryption mechanism of equivalent strength and vetted reputation is used for all access-controlled pages.

## Related weaknesses

- CWE-319 (ChildOf)

## Source

- [CWE-5 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/5.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
