---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-639"
status: "Incomplete"
---
# CWE-639: Authorization Bypass Through User-Controlled Key

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The system's authorization functionality does not prevent one user from gaining access to another user's data or record by modifying the key value identifying the data.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** For each and every data access, ensure that the user has sufficient privilege to access the record that is being requested.
- **Architecture and Design:** Make sure that the key that is used in the lookup of a specific user's record is not controllable externally by the user or that any tampering can be detected.
- **Architecture and Design:** Use encryption in order to make it more difficult to guess other legitimate values of the key or associate a digital signature with the key so that the server can verify that there has been no tampering.

## Related weaknesses

- CWE-863 (ChildOf)
- CWE-863 (ChildOf)
- CWE-284 (ChildOf)

## Source

- [CWE-639 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/639.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
