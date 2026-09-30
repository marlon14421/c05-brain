---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1016"
target_object: "T1113"
stix_relationship_id: "relationship--2fb2a011-a35a-403a-a86b-d5489b1fa5c6"
---
# Relationship 6393: S1016 — uses → T1113

**Source object:** [[01 ATT&CK/S1016 - MacMa|S1016: MacMa]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MacMa](https://attack.mitre.org/software/S1016) has used Apple’s Core Graphic APIs, such as `CGWindowListCreateImageFromArray`, to capture the user's screen and open windows.(Citation: ESET DazzleSpy Jan 2022)(Citation: Objective-See MacMa Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2fb2a011-a35a-403a-a86b-d5489b1fa5c6`.
