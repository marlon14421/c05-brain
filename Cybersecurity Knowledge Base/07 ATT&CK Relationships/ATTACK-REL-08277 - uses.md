---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1233"
target_object: "T1057"
stix_relationship_id: "relationship--edb14d5c-992a-4cd0-a0f3-b2db3f6b813c"
---
# Relationship 8277: S1233 — uses → T1057

**Source object:** [[01 ATT&CK/S1233 - PAKLOG|S1233: PAKLOG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PAKLOG](https://attack.mitre.org/software/S1233) has detected and logged the full path of processes active in the foreground using Windows API calls.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--edb14d5c-992a-4cd0-a0f3-b2db3f6b813c`.
