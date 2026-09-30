---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1277"
status: "Draft"
---
# CWE-1277: Firmware Not Updateable

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product does not provide its users with the ability to update or patch its firmware to address any vulnerabilities or weaknesses that may be present.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Specify requirements to include the ability to update the firmware. Include integrity checks and authentication to ensure that untrusted firmware cannot be installed.
- **Architecture and Design:** Design the device to allow for updating the firmware. Ensure that the design specifies how to distribute the updates and ensure their integrity and authentication.
- **Implementation:** Implement the necessary functionality to allow the firmware to be updated.

## Related weaknesses

- CWE-1329 (ChildOf)

## Source

- [CWE-1277 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1277.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
