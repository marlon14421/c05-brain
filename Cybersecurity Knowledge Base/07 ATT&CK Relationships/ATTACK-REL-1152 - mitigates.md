---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1574.012"
stix_relationship_id: "relationship--caf19942-8346-447f-9781-28a0b858c43f"
---
# Relationship 1152: M1038 — mitigates → T1574.012

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1574.012 - COR_PROFILER|T1574.012: COR_PROFILER]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Identify and block potentially malicious unmanaged COR_PROFILER profiling DLLs by using application control solutions like AppLocker that are capable of auditing and/or blocking unapproved DLLs.(Citation: Beechey 2010)(Citation: Windows Commands JPCERT)(Citation: NSA MS AppLocker)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--caf19942-8346-447f-9781-28a0b858c43f`.
