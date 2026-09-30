---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1016"
target_object: "T1053.005"
stix_relationship_id: "relationship--3ca53c3c-ec7d-4453-a80f-2f3306358a2f"
---
# Relationship 6053: G1016 — uses → T1053.005

**Source object:** [[01 ATT&CK/G1016 - FIN13|G1016: FIN13]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN13](https://attack.mitre.org/groups/G1016) has created scheduled tasks in the `C:\Windows` directory of the compromised network.(Citation: Mandiant FIN13 Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ca53c3c-ec7d-4453-a80f-2f3306358a2f`.
