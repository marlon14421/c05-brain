---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0338"
target_object: "T1125"
stix_relationship_id: "relationship--17bee216-d5ff-4e66-b221-0129be41b4f5"
---
# Relationship 6145: S0338 — uses → T1125

**Source object:** [[01 ATT&CK/S0338 - Cobian RAT|S0338: Cobian RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobian RAT](https://attack.mitre.org/software/S0338) has a feature to access the webcam on the victim’s machine.(Citation: Zscaler Cobian Aug 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--17bee216-d5ff-4e66-b221-0129be41b4f5`.
