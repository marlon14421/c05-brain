---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-201"
status: "Draft"
---
# CWE-201: Insertion of Sensitive Information Into Sent Data

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The code transmits data to another actor, but a portion of the data includes sensitive information that should not be accessible to that actor.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Specify which data in the software should be regarded as sensitive. Consider which types of users should have access to which types of data.
- **Implementation:** Ensure that any possibly sensitive data specified in the requirements is verified with designers to ensure that it is either a calculated risk or mitigated elsewhere. Any information that is not necessary to the functionality should be removed in order to lower both the overhead and the possibility of security sensitive data being sent.
- **System Configuration:** Setup default error messages so that unexpected errors do not disclose sensitive information.

## Related weaknesses

- CWE-200 (ChildOf)
- CWE-209 (CanAlsoBe)
- CWE-202 (CanAlsoBe)

## Source

- [CWE-201 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/201.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
