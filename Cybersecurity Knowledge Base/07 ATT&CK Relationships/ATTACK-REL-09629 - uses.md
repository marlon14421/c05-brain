---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0517"
target_object: "T1027"
stix_relationship_id: "relationship--426db174-3cc4-4f9c-ae34-6398a86ec3bd"
---
# Relationship 9629: S0517 — uses → T1027

**Source object:** [[01 ATT&CK/S0517 - Pillowmint|S0517: Pillowmint]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pillowmint](https://attack.mitre.org/software/S0517) has obfuscated the AES key used for encryption.(Citation: Trustwave Pillowmint June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--426db174-3cc4-4f9c-ae34-6398a86ec3bd`.
