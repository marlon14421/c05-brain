---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0269"
target_object: "T1112"
stix_relationship_id: "relationship--e0999d7e-deec-446b-a86b-4c8988e20a96"
---
# Relationship 8295: S0269 — uses → T1112

**Source object:** [[01 ATT&CK/S0269 - QUADAGENT|S0269: QUADAGENT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QUADAGENT](https://attack.mitre.org/software/S0269) modifies an HKCU Registry key to store a session identifier unique to the compromised system as well as a pre-shared key used for encrypting and decrypting C2 communications.(Citation: Unit 42 QUADAGENT July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e0999d7e-deec-446b-a86b-4c8988e20a96`.
