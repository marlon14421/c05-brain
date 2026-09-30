---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0376"
target_object: "T1112"
stix_relationship_id: "relationship--0cf14628-b4c0-470a-9059-43fc562717d8"
---
# Relationship 6878: S0376 — uses → T1112

**Source object:** [[01 ATT&CK/S0376 - HOPLIGHT|S0376: HOPLIGHT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HOPLIGHT](https://attack.mitre.org/software/S0376) has modified Managed Object Format (MOF) files within the Registry to run specific commands and create persistence on the system.(Citation: US-CERT HOPLIGHT Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0cf14628-b4c0-470a-9059-43fc562717d8`.
