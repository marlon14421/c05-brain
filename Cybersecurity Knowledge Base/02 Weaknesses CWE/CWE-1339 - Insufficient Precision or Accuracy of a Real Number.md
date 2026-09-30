---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1339"
status: "Draft"
---
# CWE-1339: Insufficient Precision or Accuracy of a Real Number

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product processes a real number with an implementation in which the number's representation does not preserve required accuracy and precision in its fractional part, causing an incorrect result.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** The developer or maintainer can move to a more accurate representation of real numbers. In extreme cases, the programmer can move to representations such as ratios of BigInts which can represent real numbers to extremely fine precision. The programmer can also use the concept of an Unum real. The memory and CPU tradeoffs of this change must be examined. Since floating point reals are used in many products and many locations, they are implemented in hardware and most format changes will cause the calculations to be moved into software resulting in slower products.

## Related weaknesses

- CWE-682 (ChildOf)
- CWE-190 (PeerOf)
- CWE-834 (CanPrecede)
- CWE-119 (CanPrecede)

## Source

- [CWE-1339 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1339.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
