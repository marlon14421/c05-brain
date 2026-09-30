---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0031"
target_object: "T1132.002"
stix_relationship_id: "relationship--6c0aae73-fe06-4aa3-8216-568d78747c6d"
---
# Relationship 9026: S0031 — uses → T1132.002

**Source object:** [[01 ATT&CK/S0031 - BACKSPACE|S0031: BACKSPACE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.002 - Non-Standard Encoding|T1132.002: Non-Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Newer variants of [BACKSPACE](https://attack.mitre.org/software/S0031) will encode C2 communications with a custom system.(Citation: FireEye APT30)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c0aae73-fe06-4aa3-8216-568d78747c6d`.
