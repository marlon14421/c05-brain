---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1427"
status: "Incomplete"
---
# CWE-1427: Improper Neutralization of Input Used for LLM Prompting

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, AI/ML

## Description

The product uses externally-provided data to build prompts provided to large language models (LLMs), but the way these prompts are constructed causes the LLM to fail to distinguish between user-supplied inputs and developer provided system directives.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-77 (ChildOf)

## Source

- [CWE-1427 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1427.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
