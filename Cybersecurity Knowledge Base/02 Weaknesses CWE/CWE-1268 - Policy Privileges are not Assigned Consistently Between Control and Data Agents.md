---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1268"
status: "Draft"
---
# CWE-1268: Policy Privileges are not Assigned Consistently Between Control and Data Agents

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product's hardware-enforced access control for a particular resource improperly accounts for privilege discrepancies between control and write policies.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Access-control-policy definition and programming flow must be sufficiently tested in pre-silicon and post-silicon testing.

## Related weaknesses

- CWE-266 (ChildOf)

## Source

- [CWE-1268 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1268.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
