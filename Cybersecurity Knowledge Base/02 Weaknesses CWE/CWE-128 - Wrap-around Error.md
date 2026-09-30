---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-128"
status: "Incomplete"
---
# CWE-128: Wrap-around Error

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++

## Description

Wrap around errors occur whenever a value is incremented past the maximum value for its type and therefore "wraps around" to a very small, negative, or undefined value.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Mitigation:** Requirements specification: The choice could be made to use a language that is not susceptible to these issues.
- **Architecture and Design:** Provide clear upper and lower bounds on the scale of any protocols designed.
- **Implementation:** Perform validation on all incremented variables to ensure that they remain within reasonable bounds.

## Related weaknesses

- CWE-682 (ChildOf)
- CWE-119 (CanPrecede)
- CWE-190 (PeerOf)

## Source

- [CWE-128 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/128.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
