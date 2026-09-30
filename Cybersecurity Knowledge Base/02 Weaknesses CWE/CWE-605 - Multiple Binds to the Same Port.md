---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-605"
status: "Draft"
---
# CWE-605: Multiple Binds to the Same Port

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

When multiple sockets are allowed to bind to the same port, other services on that port may be stolen or spoofed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Policy:** Restrict server socket address to known local addresses.

## Related weaknesses

- CWE-675 (ChildOf)
- CWE-666 (ChildOf)

## Source

- [CWE-605 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/605.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
