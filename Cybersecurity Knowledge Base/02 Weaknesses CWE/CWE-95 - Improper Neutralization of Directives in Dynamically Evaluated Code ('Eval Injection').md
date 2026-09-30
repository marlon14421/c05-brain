---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-95"
status: "Incomplete"
---
# CWE-95: Improper Neutralization of Directives in Dynamically Evaluated Code ('Eval Injection')

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java, JavaScript, Python, Perl, PHP, Ruby, Interpreted, AI/ML

## Description

The product receives input from an upstream component, but it does not neutralize or incorrectly neutralizes code syntax before using the input in a dynamic evaluation call (e.g. "eval").

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** If possible, refactor your code so that it does not need to use eval() at all.

## Related weaknesses

- CWE-94 (ChildOf)

## Source

- [CWE-95 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/95.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
