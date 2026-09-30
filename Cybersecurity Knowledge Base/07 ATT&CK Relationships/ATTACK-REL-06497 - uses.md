---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0697"
target_object: "T1561.001"
stix_relationship_id: "relationship--d687171f-152f-4211-95bb-e051dc61575f"
---
# Relationship 6497: S0697 — uses → T1561.001

**Source object:** [[01 ATT&CK/S0697 - HermeticWiper|S0697: HermeticWiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.001 - Disk Content Wipe|T1561.001: Disk Content Wipe]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HermeticWiper](https://attack.mitre.org/software/S0697) has the ability to corrupt disk partitions and obtain raw disk access to destroy data.(Citation: Crowdstrike DriveSlayer February 2022)(Citation: SentinelOne Hermetic Wiper February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d687171f-152f-4211-95bb-e051dc61575f`.
