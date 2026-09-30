---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1054"
target_object: "T1685.005"
stix_relationship_id: "relationship--3c7e4671-97ef-4822-b0dd-a8288b1c6735"
---
# Relationship 9205: G1054 — uses → T1685.005

**Source object:** [[01 ATT&CK/G1054 - MirrorFace|G1054: MirrorFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685.005 - Clear Windows Event Logs|T1685.005: Clear Windows Event Logs]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirrorFace](https://attack.mitre.org/groups/G1054) has deleted Windows event logs.(Citation: JPCERT MirrorFace JUL 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c7e4671-97ef-4822-b0dd-a8288b1c6735`.
