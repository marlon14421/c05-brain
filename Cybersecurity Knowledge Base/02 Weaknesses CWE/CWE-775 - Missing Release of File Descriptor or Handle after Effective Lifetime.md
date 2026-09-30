---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-775"
status: "Incomplete"
---
# CWE-775: Missing Release of File Descriptor or Handle after Effective Lifetime

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product does not release a file descriptor or handle after its effective lifetime has ended, i.e., after the file descriptor/handle is no longer needed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-772 (ChildOf)
- CWE-404 (ChildOf)
- CWE-404 (ChildOf)

## Source

- [CWE-775 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/775.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
