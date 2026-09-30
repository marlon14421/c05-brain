---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-96"
status: "Draft"
---
# CWE-96: Improper Neutralization of Directives in Statically Saved Code ('Static Code Injection')

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** PHP, Perl, Interpreted

## Description

The product receives input from an upstream component, but it does not neutralize or incorrectly neutralizes code syntax before inserting the input into an executable resource, such as a library, configuration file, or template.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Perform proper output validation and escaping to neutralize all code syntax from data written to code files.

## Related weaknesses

- CWE-94 (ChildOf)

## Source

- [CWE-96 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/96.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
