---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1015"
target_object: "T1033"
stix_relationship_id: "relationship--4579695f-22c6-4391-a508-da942c2e0570"
---
# Relationship 7570: S1015 — uses → T1033

**Source object:** [[01 ATT&CK/S1015 - Milan|S1015: Milan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Milan](https://attack.mitre.org/software/S1015) can identify users registered to a targeted machine.(Citation: ClearSky Siamesekitten August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4579695f-22c6-4391-a508-da942c2e0570`.
