---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0697"
target_object: "T1082"
stix_relationship_id: "relationship--87a01c6d-b7a3-481f-82a9-5dee8c6f91db"
---
# Relationship 9789: S0697 — uses → T1082

**Source object:** [[01 ATT&CK/S0697 - HermeticWiper|S0697: HermeticWiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HermeticWiper](https://attack.mitre.org/software/S0697) can determine the OS version and bitness on a targeted host.(Citation: SentinelOne Hermetic Wiper February 2022)(Citation: Crowdstrike DriveSlayer February 2022)(Citation: ESET Hermetic Wizard March 2022)(Citation: Qualys Hermetic Wiper March 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87a01c6d-b7a3-481f-82a9-5dee8c6f91db`.
