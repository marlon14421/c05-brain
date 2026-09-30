---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0098"
target_object: "T1574.001"
stix_relationship_id: "relationship--9d2dfa0b-8370-4873-9b8f-4366e61be715"
---
# Relationship 7863: G0098 — uses → T1574.001

**Source object:** [[01 ATT&CK/G0098 - BlackTech|G0098: BlackTech]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackTech](https://attack.mitre.org/groups/G0098) has used DLL side loading by giving DLLs hardcoded names and placing them in searched directories.(Citation: Trend Micro Waterbear December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d2dfa0b-8370-4873-9b8f-4366e61be715`.
