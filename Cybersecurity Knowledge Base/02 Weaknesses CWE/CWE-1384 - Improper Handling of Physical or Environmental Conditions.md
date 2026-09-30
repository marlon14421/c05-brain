---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1384"
status: "Incomplete"
---
# CWE-1384: Improper Handling of Physical or Environmental Conditions

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** System on Chip, ICS/OT

## Description

The product does not properly handle unexpected physical or environmental conditions that occur naturally or are artificially induced.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** In requirements, be specific about expectations for how the product will perform when it exceeds physical and environmental boundary conditions, e.g., by shutting down.
- **Architecture and Design:** Where possible, include independent components that can detect excess environmental conditions and have the capability to shut down the product.
- **Architecture and Design:** Where possible, use shielding or other materials that can increase the adversary's workload and reduce the likelihood of being able to successfully trigger a security-related failure.

## Related weaknesses

- CWE-703 (ChildOf)

## Source

- [CWE-1384 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1384.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
