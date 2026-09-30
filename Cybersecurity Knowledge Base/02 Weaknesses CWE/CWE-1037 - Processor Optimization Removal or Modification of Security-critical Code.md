---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1037"
status: "Incomplete"
---
# CWE-1037: Processor Optimization Removal or Modification of Security-critical Code

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Processor Hardware

## Description

The developer builds a security-critical protection mechanism into the software, but the processor optimizes the execution of the program such that the mechanism is removed or modified.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-1038 (ChildOf)

## Source

- [CWE-1037 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1037.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
