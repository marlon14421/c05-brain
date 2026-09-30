---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-220"
status: "Draft"
---
# CWE-220: Storage of File With Sensitive Data Under FTP Root

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product stores sensitive data under the FTP server root with insufficient access control, which might make it accessible to untrusted parties.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Avoid storing information under the FTP root directory.
- **System Configuration:** Access control permissions should be set to prevent reading/writing of sensitive files inside/outside of the FTP directory.

## Related weaknesses

- CWE-552 (ChildOf)

## Source

- [CWE-220 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/220.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
