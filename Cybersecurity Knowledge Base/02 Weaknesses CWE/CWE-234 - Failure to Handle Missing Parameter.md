---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-234"
status: "Incomplete"
---
# CWE-234: Failure to Handle Missing Parameter

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

If too few arguments are sent to a function, the function will still pop the expected number of arguments from the stack. Potentially, a variable number of arguments could be exhausted in a function as well.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Build and Compilation:** This issue can be simply combated with the use of proper build process.
- **Implementation:** Forward declare all functions. This is the recommended solution. Properly forward declaration of all used functions will result in a compiler error if too few arguments are sent to a function.

## Related weaknesses

- CWE-233 (ChildOf)

## Source

- [CWE-234 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/234.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
