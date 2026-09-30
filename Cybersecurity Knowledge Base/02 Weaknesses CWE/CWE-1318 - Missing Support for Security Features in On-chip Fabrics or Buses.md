---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1318"
status: "Incomplete"
---
# CWE-1318: Missing Support for Security Features in On-chip Fabrics or Buses

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Processor Hardware, Not Technology-Specific

## Description

On-chip fabrics or buses either do not support or are not configured to support privilege separation or other security features, such as access control.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** If fabric does not support security features, implement security checks in a bridge or any component that is between the master and the fabric. Alternatively, connect all fabric slaves that do not have any security assets under one such fabric and connect peripherals with security assets to a different fabric that supports security features.

## Related weaknesses

- CWE-693 (ChildOf)

## Source

- [CWE-1318 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1318.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
