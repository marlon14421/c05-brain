---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0338"
target_object: "T1113"
stix_relationship_id: "relationship--0f64f141-1f0f-4374-879d-b08f0fda8979"
---
# Relationship 5260: S0338 — uses → T1113

**Source object:** [[01 ATT&CK/S0338 - Cobian RAT|S0338: Cobian RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobian RAT](https://attack.mitre.org/software/S0338) has a feature to perform screen capture.(Citation: Zscaler Cobian Aug 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f64f141-1f0f-4374-879d-b08f0fda8979`.
