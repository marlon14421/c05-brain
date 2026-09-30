---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1392"
status: "Incomplete"
---
# CWE-1392: Use of Default Credentials

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, ICS/OT, Not Technology-Specific

## Description

The product uses default credentials (such as passwords or cryptographic keys) for potentially critical functionality.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Prohibit use of default, hard-coded, or other values that do not vary for each installation of the product - especially for separate organizations.
- **Architecture and Design:** Force the administrator to change the credential upon installation.
- **Installation:** The product administrator could change the defaults upon installation or during operation.

## Related weaknesses

- CWE-1391 (ChildOf)

## Source

- [CWE-1392 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1392.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
