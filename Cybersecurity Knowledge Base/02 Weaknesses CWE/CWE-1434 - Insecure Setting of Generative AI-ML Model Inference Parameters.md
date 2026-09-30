---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1434"
status: "Draft"
---
# CWE-1434: Insecure Setting of Generative AI/ML Model Inference Parameters

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Architecture-Specific, AI/ML, Not Technology-Specific

## Description

The product has a component that relies on a generative AI/ML model configured with inference parameters that produce an unacceptably high rate of erroneous or unexpected outputs.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Develop and adhere to robust parameter tuning processes that include extensive testing and validation.
- **Implementation:** Implement feedback mechanisms to continuously assess and adjust model performance.
- **Documentation:** Provide comprehensive documentation and guidelines for parameter settings to ensure consistent and accurate model behavior.

## Related weaknesses

- CWE-440 (ChildOf)
- CWE-665 (ChildOf)
- CWE-684 (CanPrecede)
- CWE-691 (PeerOf)

## Source

- [CWE-1434 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1434.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
