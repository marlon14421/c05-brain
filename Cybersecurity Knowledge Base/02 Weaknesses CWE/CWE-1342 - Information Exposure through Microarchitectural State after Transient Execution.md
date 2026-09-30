---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1342"
status: "Incomplete"
---
# CWE-1342: Information Exposure through Microarchitectural State after Transient Execution

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Workstation, x86, ARM, Other, Not Technology-Specific, System on Chip

## Description

The processor does not properly clear microarchitectural state after incorrect microcode assists or speculative execution, resulting in transient execution.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Hardware ensures that no illegal data flows from faulting micro-ops exists at the microarchitectural level.
- **Build and Compilation:** Include instructions that explicitly remove traces of unneeded computations from software interactions with microarchitectural elements e.g. lfence, sfence, mfence, clflush.

## Related weaknesses

- CWE-226 (ChildOf)
- CWE-226 (ChildOf)

## Source

- [CWE-1342 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1342.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
