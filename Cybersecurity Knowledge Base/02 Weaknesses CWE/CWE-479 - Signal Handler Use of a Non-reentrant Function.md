---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-479"
status: "Draft"
---
# CWE-479: Signal Handler Use of a Non-reentrant Function

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

The product defines a signal handler that calls a non-reentrant function.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Require languages or libraries that provide reentrant functionality, or otherwise make it easier to avoid this weakness.
- **Architecture and Design:** Design signal handlers to only set flags rather than perform complex functionality.
- **Implementation:** Ensure that non-reentrant functions are not found in signal handlers.
- **Implementation:** Use sanity checks to reduce the timing window for exploitation of race conditions. This is only a partial solution, since many attacks might fail, but other attacks still might work within the narrower window, even accidentally.

## Related weaknesses

- CWE-828 (ChildOf)
- CWE-663 (ChildOf)
- CWE-123 (CanPrecede)

## Source

- [CWE-479 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/479.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
