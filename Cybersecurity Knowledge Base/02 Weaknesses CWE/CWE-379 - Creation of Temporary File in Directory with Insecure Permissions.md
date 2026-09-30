---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-379"
status: "Incomplete"
---
# CWE-379: Creation of Temporary File in Directory with Insecure Permissions

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product creates a temporary file in a directory whose permissions allow unintended actors to determine the file's existence or otherwise access that file.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Many contemporary languages have functions which properly handle this condition. Older C temp file functions are especially susceptible.
- **Implementation:** Try to store sensitive tempfiles in a directory which is not world readable -- i.e., per-user directories.
- **Implementation:** Avoid using vulnerable temp file functions.

## Related weaknesses

- CWE-377 (ChildOf)

## Source

- [CWE-379 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/379.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
