---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-378"
status: "Draft"
---
# CWE-378: Creation of Temporary File With Insecure Permissions

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

Opening temporary files without appropriate measures or controls can leave the file, its contents and any function that it impacts vulnerable to attack.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Many contemporary languages have functions which properly handle this condition. Older C temp file functions are especially susceptible.
- **Implementation:** Ensure that you use proper file permissions. This can be achieved by using a safe temp file function. Temporary files should be writable and readable only by the process that owns the file.
- **Implementation:** Randomize temporary file names. This can also be achieved by using a safe temp-file function. This will ensure that temporary files will not be created in predictable places.

## Related weaknesses

- CWE-377 (ChildOf)

## Source

- [CWE-378 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/378.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
