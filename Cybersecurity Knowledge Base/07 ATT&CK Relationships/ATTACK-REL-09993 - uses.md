---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9036"
target_object: "T1027.013"
stix_relationship_id: "relationship--ed824ba0-c929-4766-942b-8c2307007cbe"
---
# Relationship 9993: S9036 — uses → T1027.013

**Source object:** [[01 ATT&CK/S9036 - LP-Notes|S9036: LP-Notes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LP-Notes](https://attack.mitre.org/software/S9036) has used a custom addition-based function and a string stacking function for string encryption.(Citation: ESET_MuddyWater_Dec2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed824ba0-c929-4766-942b-8c2307007cbe`.
