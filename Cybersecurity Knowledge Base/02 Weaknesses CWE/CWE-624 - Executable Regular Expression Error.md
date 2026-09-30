---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-624"
status: "Incomplete"
---
# CWE-624: Executable Regular Expression Error

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** PHP, Perl

## Description

The product uses a regular expression that either (1) contains an executable component with user-controlled inputs, or (2) allows a user to enable execution by inserting pattern modifiers.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** The regular expression feature in some languages allows inputs to be quoted or escaped before insertion, such as \Q and \E in Perl.

## Related weaknesses

- CWE-77 (ChildOf)
- CWE-77 (ChildOf)
- CWE-77 (ChildOf)

## Source

- [CWE-624 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/624.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
