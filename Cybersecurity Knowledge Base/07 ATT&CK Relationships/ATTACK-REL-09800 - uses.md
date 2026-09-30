---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1167"
target_object: "T1561.001"
stix_relationship_id: "relationship--cc2e4eb6-8fd6-45bb-94d8-765fafaeee3d"
---
# Relationship 9800: S1167 — uses → T1561.001

**Source object:** [[01 ATT&CK/S1167 - AcidPour|S1167: AcidPour]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.001 - Disk Content Wipe|T1561.001: Disk Content Wipe]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AcidPour](https://attack.mitre.org/software/S1167) includes functionality to overwrite victim devices with the content of a buffer to wipe disk content.(Citation: SentinelOne AcidPour 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc2e4eb6-8fd6-45bb-94d8-765fafaeee3d`.
