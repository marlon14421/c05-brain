---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-77"
status: "Draft"
---
# CWE-77: Improper Neutralization of Special Elements used in a Command ('Command Injection')

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, AI/ML

## Description

The product constructs all or part of a command using externally-influenced input from an upstream component, but it does not neutralize or incorrectly neutralizes special elements that could modify the intended command when it is sent to a downstream component.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** If at all possible, use library calls rather than external processes to recreate the desired functionality.
- **Implementation:** If possible, ensure that all external commands called from the program are statically created.
- **Operation:** Run time: Run time policy enforcement may be used in an allowlist fashion to prevent use of any non-sanctioned commands.
- **System Configuration:** Assign permissions that prevent the user from accessing/opening privileged files.

## Related weaknesses

- CWE-74 (ChildOf)
- CWE-74 (ChildOf)

## Source

- [CWE-77 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/77.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
