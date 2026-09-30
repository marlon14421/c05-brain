---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-527"
status: "Incomplete"
---
# CWE-527: Exposure of Version-Control Repository to an Unauthorized Control Sphere

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based

## Description

The product stores a CVS, git, or other repository in a directory, archive, or other resource that is stored, transferred, or otherwise made accessible to unauthorized actors.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Operation:** Recommendations include removing any CVS directories and repositories from the production server, disabling the use of remote CVS repositories, and ensuring that the latest CVS patches and version updates have been performed.

## Related weaknesses

- CWE-552 (ChildOf)

## Source

- [CWE-527 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/527.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
