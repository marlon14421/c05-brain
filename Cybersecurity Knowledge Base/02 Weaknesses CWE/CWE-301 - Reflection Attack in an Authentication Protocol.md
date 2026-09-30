---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-301"
status: "Draft"
---
# CWE-301: Reflection Attack in an Authentication Protocol

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

Simple authentication protocols are subject to reflection attacks if a malicious user can use the target machine to impersonate a trusted user.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use different keys for the initiator and responder or of a different type of challenge for the initiator and responder.
- **Architecture and Design:** Let the initiator prove its identity before proceeding.

## Related weaknesses

- CWE-1390 (ChildOf)
- CWE-327 (PeerOf)

## Source

- [CWE-301 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/301.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
