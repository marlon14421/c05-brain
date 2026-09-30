---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1303"
status: "Draft"
---
# CWE-1303: Non-Transparent Sharing of Microarchitectural Resources

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

Hardware structures shared across execution contexts (e.g., caches and branch predictors) can violate the expected architecture isolation between contexts.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Microarchitectural covert channels can be addressed using a mixture of hardware and software mitigation techniques. These include partitioned caches, new barrier and flush instructions, and disabling high resolution performance counters and timers.
- **Requirements:** Microarchitectural covert channels can be addressed using a mixture of hardware and software mitigation techniques. These include partitioned caches, new barrier and flush instructions, and disabling high resolution performance counters and timers.

## Related weaknesses

- CWE-1189 (ChildOf)
- CWE-203 (ChildOf)

## Source

- [CWE-1303 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1303.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
