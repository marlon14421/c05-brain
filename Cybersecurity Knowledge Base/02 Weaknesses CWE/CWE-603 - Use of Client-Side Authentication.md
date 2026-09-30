---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-603"
status: "Draft"
---
# CWE-603: Use of Client-Side Authentication

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, ICS/OT

## Description

A client/server product performs authentication within client code but not in server code, allowing server-side authentication to be bypassed via a modified client that omits the authentication check.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not rely on client side data. Always perform server side authentication.

## Related weaknesses

- CWE-1390 (ChildOf)
- CWE-602 (ChildOf)
- CWE-300 (PeerOf)
- CWE-656 (PeerOf)

## Source

- [CWE-603 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/603.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
