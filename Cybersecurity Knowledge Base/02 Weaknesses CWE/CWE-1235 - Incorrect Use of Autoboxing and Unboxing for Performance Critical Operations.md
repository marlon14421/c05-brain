---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1235"
status: "Incomplete"
---
# CWE-1235: Incorrect Use of Autoboxing and Unboxing for Performance Critical Operations

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java, C#, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The code uses boxed primitives, which may introduce inefficiencies into performance-critical operations.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use of boxed primitives should be limited to certain situations such as when calling methods with typed parameters. They should not be used for scientific computing or other performance critical operations. They are only suited to support "impedance mismatch" between reference types and primitives. Examine the use of boxed primitives prior to use. Use SparseArrays or ArrayMap instead of HashMap to avoid performance overhead.

## Related weaknesses

- CWE-400 (ChildOf)

## Source

- [CWE-1235 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1235.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
