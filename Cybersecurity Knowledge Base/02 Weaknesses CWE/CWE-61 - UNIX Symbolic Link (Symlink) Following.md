---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-61"
status: "Incomplete"
---
# CWE-61: UNIX Symbolic Link (Symlink) Following

**Abstraction:** Compound  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product, when opening a file or directory, does not sufficiently account for when the file is a symbolic link that resolves to a target outside of the intended control sphere. This could allow an attacker to cause the product to operate on unauthorized files.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Symbolic link attacks often occur when a program creates a tmp directory that stores files/links. Access to the directory should be restricted to the program as to prevent attackers from manipulating the files.

## Related weaknesses

- CWE-59 (ChildOf)
- CWE-362 (Requires)
- CWE-340 (Requires)
- CWE-386 (Requires)
- CWE-732 (Requires)

## Source

- [CWE-61 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/61.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
