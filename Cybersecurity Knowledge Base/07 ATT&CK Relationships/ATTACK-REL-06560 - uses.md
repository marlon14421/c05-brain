---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0465"
target_object: "T1027"
stix_relationship_id: "relationship--d8557c07-240a-4dbb-b372-1111a05a5303"
---
# Relationship 6560: S0465 — uses → T1027

**Source object:** [[01 ATT&CK/S0465 - CARROTBALL|S0465: CARROTBALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CARROTBALL](https://attack.mitre.org/software/S0465) has used a custom base64 alphabet to decode files.(Citation: Unit 42 CARROTBAT January 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8557c07-240a-4dbb-b372-1111a05a5303`.
