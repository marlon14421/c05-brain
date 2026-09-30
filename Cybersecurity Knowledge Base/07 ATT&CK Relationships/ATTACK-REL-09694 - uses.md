---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0056"
target_object: "T1016"
stix_relationship_id: "relationship--7a7c6567-1177-4ead-9fba-d6c1d3fc719b"
---
# Relationship 9694: C0056 — uses → T1016

**Source object:** [[01 ATT&CK/C0056 - RedPenguin|C0056: RedPenguin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [RedPenguin](https://attack.mitre.org/campaigns/C0056), [UNC3886](https://attack.mitre.org/groups/G1048) leveraged JunoOS CLI queries to obtain the interface index which contains system and network details.(Citation: Mandiant UNC3886 Juniper Routers MAR 2025)(Citation: Juniper RedPenguin MAR 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a7c6567-1177-4ead-9fba-d6c1d3fc719b`.
