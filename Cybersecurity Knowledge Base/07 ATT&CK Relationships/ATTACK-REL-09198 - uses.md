---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0056"
target_object: "S1219"
stix_relationship_id: "relationship--3395c92f-8d9b-4aea-9001-07ad42f318d2"
---
# Relationship 9198: C0056 — uses → S1219

**Source object:** [[01 ATT&CK/C0056 - RedPenguin|C0056: RedPenguin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1219 - REPTILE|S1219: REPTILE]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[REPTILE](https://attack.mitre.org/software/S1219) was used for command execution and persistence during [RedPenguin](https://attack.mitre.org/campaigns/C0056).(Citation: Mandiant UNC3886 Juniper Routers MAR 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3395c92f-8d9b-4aea-9001-07ad42f318d2`.
