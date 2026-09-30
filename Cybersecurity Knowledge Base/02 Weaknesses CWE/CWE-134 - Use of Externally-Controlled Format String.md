---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-134"
status: "Draft"
---
# CWE-134: Use of Externally-Controlled Format String

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, C, C++, Perl

## Description

The product uses a function that accepts a format string as an argument, but the format string originates from an external source.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Choose a language that is not subject to this flaw.
- **Implementation:** Ensure that all format string functions are passed a static string which cannot be controlled by the user, and that the proper number of arguments are always sent to that function as well. If at all possible, use functions that do not support the %n operator in format strings. [REF-116] [REF-117]
- **Build and Compilation:** Run compilers and linkers with high warning levels, since they may detect incorrect usage.

## Related weaknesses

- CWE-668 (ChildOf)
- CWE-668 (ChildOf)
- CWE-123 (CanPrecede)
- CWE-20 (ChildOf)

## Source

- [CWE-134 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/134.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
