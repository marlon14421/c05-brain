---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1113"
stix_relationship_id: "relationship--bf53c414-9ea5-4f56-8f73-eb7d2287f651"
---
# Relationship 8349: G0094 — uses → T1113

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has captured browser screenshots using [TRANSLATEXT](https://attack.mitre.org/software/S1201).(Citation: Zscaler Kimsuky TRANSLATEXT) [Kimsuky](https://attack.mitre.org/groups/G0094) has also obtained screen captures with custom malware.(Citation: Gen Digital Kimsuky HTTPTroy October 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf53c414-9ea5-4f56-8f73-eb7d2287f651`.
