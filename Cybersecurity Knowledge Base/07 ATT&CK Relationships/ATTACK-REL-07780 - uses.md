---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0056"
target_object: "T1090.003"
stix_relationship_id: "relationship--e40578ef-e703-428e-874d-6fcee8a32d2f"
---
# Relationship 7780: C0056 — uses → T1090.003

**Source object:** [[01 ATT&CK/C0056 - RedPenguin|C0056: RedPenguin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [RedPenguin](https://attack.mitre.org/campaigns/C0056), [UNC3886](https://attack.mitre.org/groups/G1048) used infrastructure associated with operational relay box (ORB) networks.(Citation: Mandiant UNC3886 Juniper Routers MAR 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e40578ef-e703-428e-874d-6fcee8a32d2f`.
