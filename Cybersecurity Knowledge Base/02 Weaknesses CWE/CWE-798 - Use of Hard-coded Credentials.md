---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-798"
status: "Draft"
---
# CWE-798: Use of Hard-coded Credentials

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Mobile, ICS/OT

## Description

The product contains hard-coded credentials, such as a password or cryptographic key.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** For inbound authentication: Rather than hard-code a default username and password, key, or other authentication credentials for first time logins, utilize a "first login" mode that requires the user to enter a unique strong password or key.
- **Architecture and Design:** If the product must contain hard-coded credentials or they cannot be removed, perform access control checks and limit which entities can access the feature that requires the hard-coded credentials. For example, a feature might only be enabled through the system console instead of through a network connection.

## Related weaknesses

- CWE-1391 (ChildOf)
- CWE-287 (ChildOf)
- CWE-344 (ChildOf)
- CWE-671 (ChildOf)
- CWE-257 (PeerOf)

## Source

- [CWE-798 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/798.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
