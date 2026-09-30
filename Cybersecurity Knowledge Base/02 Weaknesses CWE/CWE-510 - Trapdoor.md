---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-510"
status: "Incomplete"
---
# CWE-510: Trapdoor

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

A trapdoor is a hidden piece of code that responds to a special input, allowing its user access to resources without passing through the normal security enforcement mechanism.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Installation:** Always verify the integrity of the software that is being installed.
- **Testing:** Identify and closely inspect the conditions for entering privileged areas of the code, especially those related to authentication, process invocation, and network communications.

## Related weaknesses

- CWE-506 (ChildOf)

## Source

- [CWE-510 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/510.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
