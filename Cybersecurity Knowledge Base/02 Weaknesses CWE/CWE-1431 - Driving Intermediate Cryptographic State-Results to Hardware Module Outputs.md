---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1431"
status: "Incomplete"
---
# CWE-1431: Driving Intermediate Cryptographic State/Results to Hardware Module Outputs

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Architecture-Specific, System on Chip

## Description

The product uses a hardware module implementing a cryptographic algorithm that writes sensitive information about the intermediate state or results of its cryptographic operations via one of its output wires (typically the output port containing the final result).

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-200 (ChildOf)
- CWE-497 (PeerOf)

## Source

- [CWE-1431 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1431.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
