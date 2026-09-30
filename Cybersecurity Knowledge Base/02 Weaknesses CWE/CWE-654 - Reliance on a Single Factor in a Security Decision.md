---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-654"
status: "Draft"
---
# CWE-654: Reliance on a Single Factor in a Security Decision

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

A protection mechanism relies exclusively, or to a large extent, on the evaluation of a single condition or the integrity of a single object or entity in order to make a decision about granting access to restricted resources or functionality.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use multiple simultaneous checks before granting access to critical operations or granting critical privileges. A weaker but helpful mitigation is to use several successive checks (multiple layers of security).
- **Architecture and Design:** Use redundant access rules on different choke points (e.g., firewalls).

## Related weaknesses

- CWE-657 (ChildOf)
- CWE-693 (ChildOf)

## Source

- [CWE-654 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/654.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
