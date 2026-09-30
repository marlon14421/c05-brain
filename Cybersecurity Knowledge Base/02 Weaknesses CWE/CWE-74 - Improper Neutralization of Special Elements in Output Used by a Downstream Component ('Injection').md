---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-74"
status: "Incomplete"
---
# CWE-74: Improper Neutralization of Special Elements in Output Used by a Downstream Component ('Injection')

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product constructs all or part of a command, data structure, or record using externally-influenced input from an upstream component, but it does not neutralize or incorrectly neutralizes special elements that could modify how it is parsed or interpreted when it is sent to a downstream component.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Programming languages and supporting technologies might be chosen which are not subject to these issues.
- **Implementation:** Utilize an appropriate mix of allowlist and denylist parsing to filter control-plane syntax from all input.

## Related weaknesses

- CWE-707 (ChildOf)

## Source

- [CWE-74 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/74.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
