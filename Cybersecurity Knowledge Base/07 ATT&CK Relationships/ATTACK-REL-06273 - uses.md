---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1037"
target_object: "T1132.001"
stix_relationship_id: "relationship--e48c9be7-6a02-4170-a63a-204c6308a825"
---
# Relationship 6273: S1037 — uses → T1132.001

**Source object:** [[01 ATT&CK/S1037 - STARWHALE|S1037: STARWHALE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[STARWHALE](https://attack.mitre.org/software/S1037) has the ability to hex-encode collected data from an infected host.(Citation: DHS CISA AA22-055A MuddyWater February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e48c9be7-6a02-4170-a63a-204c6308a825`.
