---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1386"
status: "Incomplete"
---
# CWE-1386: Insecure Operation on Windows Junction / Mount Point

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Windows

## Description

The product opens a file or directory, but it does not properly prevent the name from being associated with a junction or mount point to a destination that is outside of the intended control sphere.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** When designing software that will have different rights than the executer, the software should check that files that it is interacting with are not improper hard links or mount points. One way to do this in Windows is to use the functionality embedded in the following command: "dir /al /s /b" or, in PowerShell, use LinkType as a filter. In addition, some software uses authentication via signing to ensure that the file is the correct one to use. Make checks atomic with the file action, otherwise a TOCTOU weakness (CWE-367) can be introduced.

## Related weaknesses

- CWE-59 (ChildOf)

## Source

- [CWE-1386 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1386.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
