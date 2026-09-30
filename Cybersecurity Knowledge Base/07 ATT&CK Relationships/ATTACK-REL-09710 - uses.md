---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1085"
target_object: "T1571"
stix_relationship_id: "relationship--9ee6eb40-881c-4928-a036-58a8df0e8f95"
---
# Relationship 9710: S1085 — uses → T1571

**Source object:** [[01 ATT&CK/S1085 - Sardonic|S1085: Sardonic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sardonic](https://attack.mitre.org/software/S1085) has the ability to connect with actor-controlled C2 servers using a custom binary protocol over port 443.(Citation: Bitdefender Sardonic Aug 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ee6eb40-881c-4928-a036-58a8df0e8f95`.
