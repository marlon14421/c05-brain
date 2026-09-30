---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1333"
status: "Draft"
---
# CWE-1333: Inefficient Regular Expression Complexity

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product uses a regular expression with a worst-case computational complexity that is inefficient and possibly exponential.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use regular expressions that do not support backtracking, e.g. by removing nested quantifiers.
- **System Configuration:** Set backtracking limits in the configuration of the regular expression implementation, such as PHP's pcre.backtrack_limit. Also consider limits on execution time for the process.
- **Implementation:** Do not use regular expressions with untrusted input. If regular expressions must be used, avoid using backtracking in the expression.
- **Implementation:** Limit the length of the input that the regular expression will process.

## Related weaknesses

- CWE-407 (ChildOf)
- CWE-407 (ChildOf)

## Source

- [CWE-1333 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1333.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
