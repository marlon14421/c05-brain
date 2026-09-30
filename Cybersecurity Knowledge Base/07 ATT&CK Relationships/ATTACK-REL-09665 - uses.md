---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0697"
target_object: "T1112"
stix_relationship_id: "relationship--41de9761-477c-4674-aea7-64a0b0b4ab4b"
---
# Relationship 9665: S0697 — uses → T1112

**Source object:** [[01 ATT&CK/S0697 - HermeticWiper|S0697: HermeticWiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HermeticWiper](https://attack.mitre.org/software/S0697) has the ability to modify Registry keys to disable crash dumps, colors for compressed files, and pop-up information about folders and desktop items.(Citation: SentinelOne Hermetic Wiper February 2022)(Citation: Crowdstrike DriveSlayer February 2022)(Citation: Qualys Hermetic Wiper March 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41de9761-477c-4674-aea7-64a0b0b4ab4b`.
