---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-611"
status: "Draft"
---
# CWE-611: Improper Restriction of XML External Entity Reference

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, XML, Not Technology-Specific, Web Based

## Description

The product processes an XML document that can contain XML entities with URIs that resolve to documents outside of the intended sphere of control, causing the product to embed incorrect documents into its output.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Many XML parsers and validators can be configured to disable external entity expansion.

## Related weaknesses

- CWE-610 (ChildOf)
- CWE-610 (ChildOf)
- CWE-441 (PeerOf)

## Source

- [CWE-611 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/611.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
