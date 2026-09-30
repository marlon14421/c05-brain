---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-99"
status: "Draft"
---
# CWE-99: Improper Control of Resource Identifiers ('Resource Injection')

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product receives input from an upstream component, but it does not restrict or incorrectly restricts the input before it is used as an identifier for a resource that may be outside the intended sphere of control.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-74 (ChildOf)
- CWE-706 (PeerOf)
- CWE-73 (CanAlsoBe)

## Source

- [CWE-99 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/99.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
