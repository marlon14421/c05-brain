---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1394"
status: "Incomplete"
---
# CWE-1394: Use of Default Cryptographic Key

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product uses a default cryptographic key for potentially critical functionality.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Prohibit use of default, hard-coded, or other values that do not vary for each installation of the product - especially for separate organizations.
- **Architecture and Design:** Force the administrator to change the credential upon installation.
- **Installation:** The product administrator could change the defaults upon installation or during operation.

## Related weaknesses

- CWE-1392 (ChildOf)

## Source

- [CWE-1394 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1394.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
