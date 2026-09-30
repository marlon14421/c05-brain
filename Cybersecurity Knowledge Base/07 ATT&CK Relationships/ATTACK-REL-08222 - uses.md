---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0453"
target_object: "T1110.001"
stix_relationship_id: "relationship--dd8d683a-0c17-448f-b604-105e130f4b04"
---
# Relationship 8222: S0453 — uses → T1110.001

**Source object:** [[01 ATT&CK/S0453 - Pony|S0453: Pony]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110.001 - Password Guessing|T1110.001: Password Guessing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pony](https://attack.mitre.org/software/S0453) has used a small dictionary of common passwords against a collected list of local accounts.(Citation: Malwarebytes Pony April 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd8d683a-0c17-448f-b604-105e130f4b04`.
