---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1328"
status: "Draft"
---
# CWE-1328: Security Version Number Mutable to Older Versions

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Security Hardware, Not Technology-Specific

## Description

Security-version number in hardware is mutable, resulting in the ability to downgrade (roll-back) the boot firmware to vulnerable code versions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** When architecting the system, security version data should be designated for storage in registers that are either read-only or have access controls that prevent modification by an untrusted agent.
- **Implementation:** During implementation and test, security version data should be demonstrated to be read-only and access controls should be validated.

## Related weaknesses

- CWE-285 (ChildOf)
- CWE-757 (PeerOf)

## Source

- [CWE-1328 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1328.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
