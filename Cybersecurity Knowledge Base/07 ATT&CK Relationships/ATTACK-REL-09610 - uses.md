---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0466"
target_object: "T1036.001"
stix_relationship_id: "relationship--0c837763-c44c-45cc-8c44-332667481a31"
---
# Relationship 9610: S0466 — uses → T1036.001

**Source object:** [[01 ATT&CK/S0466 - WindTail|S0466: WindTail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.001 - Invalid Code Signature|T1036.001: Invalid Code Signature]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WindTail](https://attack.mitre.org/software/S0466) has been incompletely signed with revoked certificates.(Citation: objective-see windtail1 dec 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c837763-c44c-45cc-8c44-332667481a31`.
