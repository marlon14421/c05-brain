---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0223"
target_object: "T1218.005"
stix_relationship_id: "relationship--3cd0e385-3c60-4742-b3a6-c07dbf10ba45"
---
# Relationship 9707: S0223 — uses → T1218.005

**Source object:** [[01 ATT&CK/S0223 - POWERSTATS|S0223: POWERSTATS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.005 - Mshta|T1218.005: Mshta]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POWERSTATS](https://attack.mitre.org/software/S0223) can use Mshta.exe to execute additional payloads on compromised hosts.(Citation: FireEye MuddyWater Mar 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3cd0e385-3c60-4742-b3a6-c07dbf10ba45`.
