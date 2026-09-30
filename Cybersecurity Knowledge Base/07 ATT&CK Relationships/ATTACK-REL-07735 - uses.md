---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0647"
target_object: "T1113"
stix_relationship_id: "relationship--3982f2f1-8fdd-4ccd-84e6-6a13c919c4c9"
---
# Relationship 7735: S0647 — uses → T1113

**Source object:** [[01 ATT&CK/S0647 - Turian|S0647: Turian]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Turian](https://attack.mitre.org/software/S0647) has the ability to take screenshots.(Citation: ESET BackdoorDiplomacy Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3982f2f1-8fdd-4ccd-84e6-6a13c919c4c9`.
