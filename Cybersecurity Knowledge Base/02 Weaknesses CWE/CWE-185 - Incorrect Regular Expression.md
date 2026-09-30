---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-185"
status: "Draft"
---
# CWE-185: Incorrect Regular Expression

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product specifies a regular expression in a way that causes data to be improperly matched or compared.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Regular expressions can become error prone when defining a complex language even for those experienced in writing grammars. Determine if several smaller regular expressions simplify one large regular expression. Also, subject the regular expression to thorough testing techniques such as equivalence partitioning, boundary value analysis, and robustness. After testing and a reasonable confidence level is achieved, a regular expression may not be foolproof. If an exploit is allowed to slip through, then record the exploit and refactor the regular expression.

## Related weaknesses

- CWE-697 (ChildOf)
- CWE-187 (CanPrecede)
- CWE-182 (CanPrecede)

## Source

- [CWE-185 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/185.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
