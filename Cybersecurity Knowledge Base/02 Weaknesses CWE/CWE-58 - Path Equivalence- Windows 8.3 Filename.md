---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-58"
status: "Incomplete"
---
# CWE-58: Path Equivalence: Windows 8.3 Filename

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Windows, Not Technology-Specific

## Description

The product contains a protection mechanism that restricts access to a long filename on a Windows operating system, but it does not properly restrict access to the equivalent short "8.3" filename.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **System Configuration:** Disable Windows from supporting 8.3 filenames by editing the Windows registry. Preventing 8.3 filenames will not remove previously generated 8.3 filenames.

## Related weaknesses

- CWE-41 (ChildOf)

## Source

- [CWE-58 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/58.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
