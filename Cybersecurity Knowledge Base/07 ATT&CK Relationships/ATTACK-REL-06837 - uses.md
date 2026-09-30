---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0218"
target_object: "T1102.002"
stix_relationship_id: "relationship--2b789109-44c7-4195-8df8-50b1e09b1a69"
---
# Relationship 6837: S0218 — uses → T1102.002

**Source object:** [[01 ATT&CK/S0218 - SLOWDRIFT|S0218: SLOWDRIFT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SLOWDRIFT](https://attack.mitre.org/software/S0218) uses cloud based services for C2.(Citation: FireEye APT37 Feb 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b789109-44c7-4195-8df8-50b1e09b1a69`.
