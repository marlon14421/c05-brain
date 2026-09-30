---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1229"
target_object: "T1106"
stix_relationship_id: "relationship--f2f1e84a-d6c2-460b-bc80-a90366f22b42"
---
# Relationship 8807: S1229 — uses → T1106

**Source object:** [[01 ATT&CK/S1229 - Havoc|S1229: Havoc]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Havoc](https://attack.mitre.org/software/S1229) can use `NtAllocateVirtualMemory` and `NtCreateThreadEx` to aid process injection.(Citation: Havoc Framework Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f2f1e84a-d6c2-460b-bc80-a90366f22b42`.
