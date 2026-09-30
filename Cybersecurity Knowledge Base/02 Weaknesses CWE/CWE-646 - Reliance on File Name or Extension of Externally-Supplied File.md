---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-646"
status: "Incomplete"
---
# CWE-646: Reliance on File Name or Extension of Externally-Supplied File

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Server

## Description

The product allows a file to be uploaded, but it relies on the file name or extension of the file to determine the appropriate behaviors. This could be used by attackers to cause the file to be misclassified and processed in a dangerous fashion.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Make decisions on the server side based on file content and not on file name or extension.

## Related weaknesses

- CWE-345 (ChildOf)
- CWE-434 (PeerOf)

## Source

- [CWE-646 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/646.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
