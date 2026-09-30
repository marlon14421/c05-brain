---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-69"
status: "Incomplete"
---
# CWE-69: Improper Handling of Windows ::DATA Alternate Data Stream

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Windows

## Description

The product does not properly prevent access to, or detect usage of, alternate data streams (ADS).

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that the source code correctly parses the filename to read or write to the correct stream.

## Related weaknesses

- CWE-66 (ChildOf)

## Source

- [CWE-69 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/69.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
