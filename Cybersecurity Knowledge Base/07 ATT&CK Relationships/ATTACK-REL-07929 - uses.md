---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1684.001"
stix_relationship_id: "relationship--5d21c6ae-3b8b-4c3d-b71d-6d324ef80fa9"
---
# Relationship 7929: G1015 — uses → T1684.001

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) utilized social engineering to compel IT help desk personnel to reset passwords and MFA tokens.(Citation: CISA Scattered Spider Advisory November 2023)(Citation: MSTIC Octo Tempest Operations October 2023) [Scattered Spider](https://attack.mitre.org/groups/G1015) has also used Microsoft Teams to pose as internal IT support or help desk personnel.(Citation: Mandiant UNC3944 May 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5d21c6ae-3b8b-4c3d-b71d-6d324ef80fa9`.
