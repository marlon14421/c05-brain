---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-15"
status: "Incomplete"
---
# CWE-15: External Control of System or Configuration Setting

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Technology-Specific, ICS/OT

## Description

One or more system settings or configuration elements can be externally controlled by a user.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Because setting manipulation covers a diverse set of functions, any attempt at illustrating it will inevitably be incomplete. Rather than searching for a tight-knit relationship between the functions addressed in the setting manipulation category, take a step back and consider the sorts of system values that an attacker should not be allowed to control.
- **Implementation:** In general, do not allow user-provided or otherwise untrusted data to control sensitive values. The leverage that an attacker gains by controlling these values is not always immediately obvious, but do not underestimate the creativity of the attacker.

## Related weaknesses

- CWE-642 (ChildOf)
- CWE-610 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-15 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/15.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
