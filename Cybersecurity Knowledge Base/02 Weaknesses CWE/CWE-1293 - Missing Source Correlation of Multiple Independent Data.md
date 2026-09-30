---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1293"
status: "Draft"
---
# CWE-1293: Missing Source Correlation of Multiple Independent Data

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product relies on one source of data, preventing the ability to detect if an adversary has compromised a data source.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Design system to use a Practical Byzantine fault method, to request information from multiple sources to verify the data and report on potentially compromised information sources.
- **Implementation:** Failure to use a Practical Byzantine fault method when requesting data. Lack of place to report potentially compromised information sources. Relying on non-independent information sources for integrity checking. Failure to report information sources that respond in the minority to incident response procedures.

## Related weaknesses

- CWE-345 (ChildOf)
- CWE-654 (PeerOf)

## Source

- [CWE-1293 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1293.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
