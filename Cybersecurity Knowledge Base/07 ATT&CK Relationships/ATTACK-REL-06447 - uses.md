---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0438"
target_object: "T1113"
stix_relationship_id: "relationship--75a82c43-c3f2-4cec-a9cb-3407b03f27b7"
---
# Relationship 6447: S0438 — uses → T1113

**Source object:** [[01 ATT&CK/S0438 - Attor|S0438: Attor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Attor](https://attack.mitre.org/software/S0438)'s has a plugin that captures screenshots of the target applications.(Citation: ESET Attor Oct 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75a82c43-c3f2-4cec-a9cb-3407b03f27b7`.
