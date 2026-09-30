---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1017"
target_object: "T1119"
stix_relationship_id: "relationship--82b85b1c-e6f8-443a-b64a-11b63907755f"
---
# Relationship 8333: S1017 — uses → T1119

**Source object:** [[01 ATT&CK/S1017 - OutSteel|S1017: OutSteel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OutSteel](https://attack.mitre.org/software/S1017) can automatically scan for and collect files with specific extensions.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--82b85b1c-e6f8-443a-b64a-11b63907755f`.
