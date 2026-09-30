---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0047"
target_object: "T1095"
stix_relationship_id: "relationship--3c6ad797-8dba-4dee-8930-d35e26a782da"
---
# Relationship 6511: C0047 — uses → T1095

**Source object:** [[01 ATT&CK/C0047 - RedDelta Modified PlugX Infection Chain Operations|C0047: RedDelta Modified PlugX Infection Chain Operations]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) communicated over TCP 5000 from adversary administrative servers to adversary command and control nodes during [RedDelta Modified PlugX Infection Chain Operations](https://attack.mitre.org/campaigns/C0047).(Citation: Recorded Future RedDelta 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c6ad797-8dba-4dee-8930-d35e26a782da`.
