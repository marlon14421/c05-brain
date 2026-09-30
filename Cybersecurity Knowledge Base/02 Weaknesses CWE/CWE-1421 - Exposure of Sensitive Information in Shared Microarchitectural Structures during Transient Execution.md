---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1421"
status: "Incomplete"
---
# CWE-1421: Exposure of Sensitive Information in Shared Microarchitectural Structures during Transient Execution

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

A processor event may allow transient operations to access architecturally restricted data (for example, in another address space) in a shared microarchitectural structure (for example, a CPU cache), potentially exposing the data over a covert channel.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-1420 (ChildOf)
- CWE-1420 (ChildOf)

## Source

- [CWE-1421 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1421.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
