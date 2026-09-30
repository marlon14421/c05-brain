---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-182"
status: "Draft"
---
# CWE-182: Collapse of Data into Unsafe Value

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product filters data in a way that causes it to be reduced or "collapsed" into an unsafe value that violates an expected security property.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Avoid making decisions based on names of resources (e.g. files) if those resources can have alternate names.
- **Implementation:** Inputs should be decoded and canonicalized to the application's current internal representation before being validated (CWE-180). Make sure that the application does not decode the same input twice (CWE-174). Such errors could be used to bypass allowlist validation schemes by introducing dangerous inputs after they have been checked.
- **Mitigation:** Canonicalize the name to match that of the file system's representation of the name. This can sometimes be achieved with an available API (e.g. in Win32 the GetFullPathName function).

## Related weaknesses

- CWE-707 (ChildOf)
- CWE-33 (CanPrecede)
- CWE-34 (CanPrecede)
- CWE-35 (CanPrecede)

## Source

- [CWE-182 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/182.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
