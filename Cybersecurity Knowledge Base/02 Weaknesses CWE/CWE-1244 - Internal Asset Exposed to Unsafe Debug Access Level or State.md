---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1244"
status: "Stable"
---
# CWE-1244: Internal Asset Exposed to Unsafe Debug Access Level or State

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, System on Chip

## Description

The product uses physical debug or test interfaces with support for multiple access levels, but it assigns the wrong debug access level to an internal asset, providing unintended access to the asset from untrusted debug agents.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Apply blinding [REF-1219] or masking techniques in strategic areas.
- **Implementation:** Add shielding or tamper-resistant protections to the device, which increases the difficulty and cost for accessing debug/test interfaces.

## Related weaknesses

- CWE-863 (ChildOf)

## Source

- [CWE-1244 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1244.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
