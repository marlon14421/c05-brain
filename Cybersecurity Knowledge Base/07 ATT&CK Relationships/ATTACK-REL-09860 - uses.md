---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0047"
target_object: "T1082"
stix_relationship_id: "relationship--50ee9427-67e7-4db4-b931-1b872cd73e86"
---
# Relationship 9860: C0047 — uses → T1082

**Source object:** [[01 ATT&CK/C0047 - RedDelta Modified PlugX Infection Chain Operations|C0047: RedDelta Modified PlugX Infection Chain Operations]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) captured victim operating system type via User Agent analysis during [RedDelta Modified PlugX Infection Chain Operations](https://attack.mitre.org/campaigns/C0047).(Citation: Recorded Future RedDelta 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--50ee9427-67e7-4db4-b931-1b872cd73e86`.
