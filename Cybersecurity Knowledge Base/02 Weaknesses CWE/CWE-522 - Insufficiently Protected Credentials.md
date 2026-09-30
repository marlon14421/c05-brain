---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-522"
status: "Incomplete"
---
# CWE-522: Insufficiently Protected Credentials

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based, ICS/OT

## Description

The product transmits or stores authentication credentials, but it uses an insecure method that is susceptible to unauthorized interception and/or retrieval.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use an appropriate security mechanism to protect the credentials.
- **Architecture and Design:** Make appropriate use of cryptography to protect the credentials.
- **Implementation:** Use industry standards to protect the credentials (e.g. LDAP, keystore, etc.).

## Related weaknesses

- CWE-1390 (ChildOf)
- CWE-287 (ChildOf)
- CWE-668 (ChildOf)

## Source

- [CWE-522 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/522.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
