---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0242"
target_object: "T1486"
stix_relationship_id: "relationship--8c1c7c51-f9bf-4163-a01b-7d922a2d1a93"
---
# Relationship 7319: S0242 — uses → T1486

**Source object:** [[01 ATT&CK/S0242 - SynAck|S0242: SynAck]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SynAck](https://attack.mitre.org/software/S0242) encrypts the victims machine followed by asking the victim to pay a ransom. (Citation: SecureList SynAck Doppelgänging May 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c1c7c51-f9bf-4163-a01b-7d922a2d1a93`.
