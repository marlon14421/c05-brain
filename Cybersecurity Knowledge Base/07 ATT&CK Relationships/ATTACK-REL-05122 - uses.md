---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0697"
target_object: "T1561.002"
stix_relationship_id: "relationship--6a8db293-43a2-45a1-b9b2-32222355bc4e"
---
# Relationship 5122: S0697 — uses → T1561.002

**Source object:** [[01 ATT&CK/S0697 - HermeticWiper|S0697: HermeticWiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.002 - Disk Structure Wipe|T1561.002: Disk Structure Wipe]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HermeticWiper](https://attack.mitre.org/software/S0697) has the ability to corrupt disk partitions, damage the Master Boot Record (MBR), and overwrite the Master File Table (MFT) of all available physical drives.(Citation: SentinelOne Hermetic Wiper February 2022)(Citation: Symantec Ukraine Wipers February 2022)(Citation: Crowdstrike DriveSlayer February 2022)(Citation: Qualys Hermetic Wiper March 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a8db293-43a2-45a1-b9b2-32222355bc4e`.
