---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-600"
status: "Draft"
---
# CWE-600: Uncaught Exception in Servlet

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java, Web Server

## Description

The Servlet does not catch all exceptions, which may reveal sensitive debugging information.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Implement Exception blocks to handle all types of Exceptions.

## Related weaknesses

- CWE-248 (ChildOf)
- CWE-209 (CanPrecede)
- CWE-390 (PeerOf)

## Source

- [CWE-600 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/600.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
