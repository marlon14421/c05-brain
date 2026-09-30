---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1332"
status: "Stable"
---
# CWE-1332: Improper Handling of Faults that Lead to Instruction Skips

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, System on Chip

## Description

The device is missing or incorrectly implements circuitry or sensors that detect and mitigate the skipping of security-critical CPU instructions when they occur.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Design strategies for ensuring safe failure if inputs, such as Vcc, are modified out of acceptable ranges.
- **Architecture and Design:** Design strategies for ensuring safe behavior if instructions attempt to be skipped.
- **Architecture and Design:** Identify mission critical secrets that should be wiped if faulting is detected, and design a mechanism to do the deletion.
- **Implementation:** Add redundancy by performing an operation multiple times, either in space or time, and perform majority voting. Additionally, make conditional instruction timing unpredictable.
- **Implementation:** Use redundant operations or canaries to detect and respond to faults.
- **Implementation:** Ensure that fault mitigations are strong enough in practice. For example, a low power detection mechanism that takes 50 clock cycles to trigger at lower voltages may be an insufficient security mechanism if the instruction counter has already progressed with no other CPU activity occurring.

## Related weaknesses

- CWE-1384 (ChildOf)
- CWE-1247 (PeerOf)

## Source

- [CWE-1332 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1332.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
