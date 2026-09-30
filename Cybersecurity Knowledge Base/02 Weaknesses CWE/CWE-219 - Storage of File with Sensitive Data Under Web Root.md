---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-219"
status: "Draft"
---
# CWE-219: Storage of File with Sensitive Data Under Web Root

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The product stores sensitive data under the web document root with insufficient access control, which might make it accessible to untrusted parties.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Avoid storing information under the web root directory.
- **System Configuration:** Access control permissions should be set to prevent reading/writing of sensitive files inside/outside of the web directory.

## Related weaknesses

- CWE-552 (ChildOf)

## Source

- [CWE-219 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/219.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
