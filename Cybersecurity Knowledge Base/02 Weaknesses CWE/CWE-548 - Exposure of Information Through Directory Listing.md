---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-548"
status: "Draft"
---
# CWE-548: Exposure of Information Through Directory Listing

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product inappropriately exposes a directory listing with an index of all the resources located inside of the directory.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Recommendations include restricting access to important directories or files by adopting a need to know requirement for both the document and server root, and turning off features such as Automatic Directory Listings that could expose private files and provide information that could be utilized by an attacker when formulating or conducting an attack.

## Related weaknesses

- CWE-497 (ChildOf)

## Source

- [CWE-548 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/548.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
