---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-541"
status: "Incomplete"
---
# CWE-541: Inclusion of Sensitive Information in an Include File

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

If an include file source is accessible, the file can contain usernames and passwords, as well as sensitive information pertaining to the application and system.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not store sensitive information in include files.
- **Architecture and Design:** Protect include files from being exposed.

## Related weaknesses

- CWE-540 (ChildOf)

## Source

- [CWE-541 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/541.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
