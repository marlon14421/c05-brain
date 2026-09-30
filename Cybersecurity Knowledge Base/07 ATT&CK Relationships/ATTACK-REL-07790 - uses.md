---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0643"
target_object: "T1113"
stix_relationship_id: "relationship--6c10bd99-6932-451d-b739-13adf1276a22"
---
# Relationship 7790: S0643 — uses → T1113

**Source object:** [[01 ATT&CK/S0643 - Peppy|S0643: Peppy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Peppy](https://attack.mitre.org/software/S0643) can take screenshots on targeted systems.(Citation: Proofpoint Operation Transparent Tribe March 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c10bd99-6932-451d-b739-13adf1276a22`.
