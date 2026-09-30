---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1334"
status: "Draft"
---
# CWE-1334: Unauthorized Error Injection Can Degrade Hardware Redundancy

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

An unauthorized agent can inject errors into a redundant block to deprive the system of redundancy or put the system in a degraded operating mode.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Ensure the design does not allow error injection in modes intended for normal run-time operation. Provide access controls on interfaces for injecting errors.
- **Implementation:** Disallow error injection in modes which are expected to be used for normal run-time operation. Provide access controls on interfaces for injecting errors.
- **Integration:** Add an access control layer atop any unprotected interfaces for injecting errors.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1334 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1334.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
