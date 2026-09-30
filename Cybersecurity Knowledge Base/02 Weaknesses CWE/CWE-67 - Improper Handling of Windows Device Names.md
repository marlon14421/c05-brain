---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-67"
status: "Incomplete"
---
# CWE-67: Improper Handling of Windows Device Names

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Windows

## Description

The product constructs pathnames from user input, but it does not handle or incorrectly handles a pathname containing a Windows device name such as AUX or CON. This typically leads to denial of service or an information exposure when the application attempts to process the pathname as a regular file.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Be familiar with the device names in the operating system where your system is deployed. Check input for these device names.

## Related weaknesses

- CWE-66 (ChildOf)

## Source

- [CWE-67 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/67.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
