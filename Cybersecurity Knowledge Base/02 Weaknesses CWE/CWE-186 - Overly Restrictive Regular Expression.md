---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-186"
status: "Draft"
---
# CWE-186: Overly Restrictive Regular Expression

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

A regular expression is overly restrictive, which prevents dangerous values from being detected.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Regular expressions can become error prone when defining a complex language even for those experienced in writing grammars. Determine if several smaller regular expressions simplify one large regular expression. Also, subject your regular expression to thorough testing techniques such as equivalence partitioning, boundary value analysis, and robustness. After testing and a reasonable confidence level is achieved, a regular expression may not be foolproof. If an exploit is allowed to slip through, then record the exploit and refactor your regular expression.

## Related weaknesses

- CWE-185 (ChildOf)
- CWE-184 (CanAlsoBe)
- CWE-183 (CanAlsoBe)

## Source

- [CWE-186 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/186.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
