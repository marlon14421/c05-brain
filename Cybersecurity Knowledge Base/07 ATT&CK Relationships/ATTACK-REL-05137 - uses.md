---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0444"
target_object: "T1105"
stix_relationship_id: "relationship--0177d430-a0b9-4f2f-8c66-8dfa4391611a"
---
# Relationship 5137: S0444 — uses → T1105

**Source object:** [[01 ATT&CK/S0444 - ShimRat|S0444: ShimRat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShimRat](https://attack.mitre.org/software/S0444) can download additional files.(Citation: FOX-IT May 2016 Mofang)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0177d430-a0b9-4f2f-8c66-8dfa4391611a`.
