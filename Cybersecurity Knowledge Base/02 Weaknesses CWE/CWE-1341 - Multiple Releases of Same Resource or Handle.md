---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1341"
status: "Incomplete"
---
# CWE-1341: Multiple Releases of Same Resource or Handle

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java, Rust, Not Language-Specific, C, C++, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product attempts to close or release a resource or handle more than once, without any successful open between the close operations.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Change the code's logic so that the resource is only closed once. This might require simplifying or refactoring. This fix can be simple to do in small code blocks, but more difficult when multiple closes are buried within complex conditionals.
- **Implementation:** It can be effective to implement a flag that is (1) set when the resource is opened, (2) cleared when it is closed, and (3) checked before closing. This approach can be useful when there are disparate cases in which closes must be performed. However, flag-tracking can increase code complexity and requires diligent compliance by the programmer.
- **Implementation:** When closing a resource, set the resource's associated variable to NULL or equivalent value for the given language. Some APIs will ignore this null value without causing errors. For other APIs, this can lead to application crashes or exceptions, which may still be preferable to corrupting an unintended resource such as memory or data.

## Related weaknesses

- CWE-675 (ChildOf)
- CWE-672 (CanPrecede)

## Source

- [CWE-1341 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1341.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
