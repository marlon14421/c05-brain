---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-464"
status: "Incomplete"
---
# CWE-464: Addition of Data Structure Sentinel

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++

## Description

The accidental addition of a data-structure sentinel can cause serious programming logic problems.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Encapsulate the user from interacting with data sentinels. Validate user input to verify that sentinels are not present.
- **Implementation:** Proper error checking can reduce the risk of inadvertently introducing sentinel values into data. For example, if a parsing function fails or encounters an error, it might return a value that is the same as the sentinel.
- **Architecture and Design:** Use an abstraction library to abstract away risky APIs. This is not a complete solution.
- **Operation:** Use OS-level preventative functionality. This is not a complete solution.

## Related weaknesses

- CWE-138 (ChildOf)

## Source

- [CWE-464 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/464.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
