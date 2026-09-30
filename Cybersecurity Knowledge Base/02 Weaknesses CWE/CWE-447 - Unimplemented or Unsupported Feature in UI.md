---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-447"
status: "Draft"
---
# CWE-447: Unimplemented or Unsupported Feature in UI

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

A UI function for a security feature appears to be supported and gives feedback to the user that suggests that it is supported, but the underlying functionality is not implemented.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Testing:** Perform functionality testing before deploying the application.

## Related weaknesses

- CWE-446 (ChildOf)
- CWE-671 (ChildOf)

## Source

- [CWE-447 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/447.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
