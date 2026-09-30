---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1313"
status: "Draft"
---
# CWE-1313: Hardware Allows Activation of Test or Debug Logic at Runtime

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

During runtime, the hardware allows for test or debug logic (feature) to be activated, which allows for changing the state of the hardware. This feature can alter the intended behavior of the system and allow for alteration and leakage of sensitive data by an adversary.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Insert restrictions on when the hardware's test or debug features can be activated. For example, during normal operating modes, the hardware's privileged modes that allow access to such features cannot be activated. Configuring the hardware to only enter a test or debug mode within a window of opportunity such as during boot or configuration stage. The result is disablement of such test/debug features and associated modes during normal runtime operations.
- **Implementation:** Insert restrictions on when the hardware's test or debug features can be activated. For example, during normal operating modes, the hardware's privileged modes that allow access to such features cannot be activated. Configuring the hardware to only enter a test or debug mode within a window of opportunity such as during boot or configuration stage. The result is disablement of such test/debug features and associated modes during normal runtime operations.
- **Integration:** Insert restrictions on when the hardware's test or debug features can be activated. For example, during normal operating modes, the hardware's privileged modes that allow access to such features cannot be activated. Configuring the hardware to only enter a test or debug mode within a window of opportunity such as during boot or configuration stage. The result is disablement of such test/debug features and associated modes during normal runtime operations.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1313 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1313.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
