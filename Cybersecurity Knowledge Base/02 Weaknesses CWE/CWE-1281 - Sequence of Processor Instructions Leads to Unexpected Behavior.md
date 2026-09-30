---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1281"
status: "Incomplete"
---
# CWE-1281: Sequence of Processor Instructions Leads to Unexpected Behavior

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific, Processor Hardware

## Description

Specific combinations of processor instructions lead to undesirable behavior such as locking the processor until a hard reset performed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Testing:** Implement a rigorous testing strategy that incorporates randomization to explore instruction sequences that are unlikely to appear in normal workloads in order to identify halt and catch fire instruction sequences.
- **Patching and Maintenance:** Patch operating system to avoid running Halt and Catch Fire type sequences or to mitigate the damage caused by unexpected behavior. See [REF-1108].

## Related weaknesses

- CWE-691 (ChildOf)

## Source

- [CWE-1281 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1281.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
