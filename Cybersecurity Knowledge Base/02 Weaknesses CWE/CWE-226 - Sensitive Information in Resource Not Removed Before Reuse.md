---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-226"
status: "Draft"
---
# CWE-226: Sensitive Information in Resource Not Removed Before Reuse

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product releases a resource such as memory or a file so that it can be made available for reuse, but it does not clear or "zeroize" the information contained in the resource before the product performs a critical state transition or makes the resource available for reuse by other entities.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** During critical state transitions, information not needed in the next state should be removed or overwritten with fixed patterns (such as all 0's) or random data, before the transition to the next state.
- **Architecture and Design:** When releasing, de-allocating, or deleting a resource, overwrite its data and relevant metadata with fixed patterns or random data. Be cautious about complex resource types whose underlying representation might be non-contiguous or change at a low level, such as how a file might be split into different chunks on a file system, even though "logical" file positions are contiguous at the application layer. Such resource types might require invocation of special modes or APIs to tell the underlying operating system to perform the necessary clearing, such as SDelete (Secure Delete) on Windows, although the appropriate functionality might not be available at the application layer.

## Related weaknesses

- CWE-459 (ChildOf)
- CWE-212 (ChildOf)
- CWE-201 (CanPrecede)

## Source

- [CWE-226 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/226.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
