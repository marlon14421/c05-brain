---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0647"
target_object: "T1120"
stix_relationship_id: "relationship--f0a42be5-d7ec-475e-a9cd-2c4728153bb8"
---
# Relationship 5375: S0647 — uses → T1120

**Source object:** [[01 ATT&CK/S0647 - Turian|S0647: Turian]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Turian](https://attack.mitre.org/software/S0647) can scan for removable media to collect data.(Citation: ESET BackdoorDiplomacy Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0a42be5-d7ec-475e-a9cd-2c4728153bb8`.
