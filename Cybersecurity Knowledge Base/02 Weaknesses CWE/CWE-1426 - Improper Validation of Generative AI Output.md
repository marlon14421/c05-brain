---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1426"
status: "Incomplete"
---
# CWE-1426: Improper Validation of Generative AI Output

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Architecture-Specific, AI/ML, Not Technology-Specific

## Description

The product invokes a generative AI/ML component whose behaviors and outputs cannot be directly controlled, but the product does not validate or insufficiently validates the outputs to ensure that they align with the intended security, content, or privacy policy.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Since the output from a generative AI component (such as an LLM) cannot be trusted, ensure that it operates in an untrusted or non-privileged space.
- **Operation:** Use "semantic comparators," which are mechanisms that provide semantic comparison to identify objects that might appear different but are semantically similar.

## Related weaknesses

- CWE-707 (ChildOf)

## Source

- [CWE-1426 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1426.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
