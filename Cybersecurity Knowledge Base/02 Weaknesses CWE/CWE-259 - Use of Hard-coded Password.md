---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-259"
status: "Draft"
---
# CWE-259: Use of Hard-coded Password

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, ICS/OT

## Description

The product contains a hard-coded password, which it uses for its own inbound authentication or for outbound communication to external components.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** For outbound authentication: store passwords outside of the code in a strongly-protected, encrypted configuration file or database that is protected from access by all outsiders, including other local users on the same system. Properly protect the key (CWE-320). If you cannot use encryption to protect the file, then make sure that the permissions are as restrictive as possible.
- **Architecture and Design:** For inbound authentication: Rather than hard-code a default username and password for first time logins, utilize a "first login" mode that requires the user to enter a unique strong password.
- **Architecture and Design:** Perform access control checks and limit which entities can access the feature that requires the hard-coded password. For example, a feature might only be enabled through the system console instead of through a network connection.

## Related weaknesses

- CWE-798 (ChildOf)
- CWE-798 (ChildOf)
- CWE-798 (ChildOf)
- CWE-321 (PeerOf)
- CWE-257 (PeerOf)

## Source

- [CWE-259 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/259.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
