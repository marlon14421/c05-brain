---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0152"
target_object: "T1113"
stix_relationship_id: "relationship--b2b873cd-8618-426e-9cae-9e6755acafad"
---
# Relationship 7549: S0152 — uses → T1113

**Source object:** [[01 ATT&CK/S0152 - EvilGrab|S0152: EvilGrab]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[EvilGrab](https://attack.mitre.org/software/S0152) has the capability to capture screenshots.(Citation: PWC Cloud Hopper Technical Annex April 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b2b873cd-8618-426e-9cae-9e6755acafad`.
