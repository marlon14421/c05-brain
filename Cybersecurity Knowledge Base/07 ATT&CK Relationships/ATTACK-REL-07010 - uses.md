---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0445"
target_object: "T1105"
stix_relationship_id: "relationship--137f13ee-0607-47ba-952b-dbe39c1330bb"
---
# Relationship 7010: S0445 — uses → T1105

**Source object:** [[01 ATT&CK/S0445 - ShimRatReporter|S0445: ShimRatReporter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShimRatReporter](https://attack.mitre.org/software/S0445) had the ability to download additional payloads.(Citation: FOX-IT May 2016 Mofang)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--137f13ee-0607-47ba-952b-dbe39c1330bb`.
