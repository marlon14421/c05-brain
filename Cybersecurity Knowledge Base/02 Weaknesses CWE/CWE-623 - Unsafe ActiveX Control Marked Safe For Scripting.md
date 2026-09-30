---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-623"
status: "Draft"
---
# CWE-623: Unsafe ActiveX Control Marked Safe For Scripting

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Web Based

## Description

An ActiveX control is intended for restricted use, but it has been marked as safe-for-scripting.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** During development, do not mark it as safe for scripting.
- **System Configuration:** After distribution, you can set the kill bit for the control so that it is not accessible from Internet Explorer.

## Related weaknesses

- CWE-267 (ChildOf)
- CWE-618 (PeerOf)

## Source

- [CWE-623 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/623.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
