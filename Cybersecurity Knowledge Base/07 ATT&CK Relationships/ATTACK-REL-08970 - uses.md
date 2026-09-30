---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0449"
target_object: "T1486"
stix_relationship_id: "relationship--006e029e-0714-4f99-befd-53b9fbc7c8c8"
---
# Relationship 8970: S0449 — uses → T1486

**Source object:** [[01 ATT&CK/S0449 - Maze|S0449: Maze]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Maze](https://attack.mitre.org/software/S0449) has disrupted systems by encrypting files on targeted machines, claiming to decrypt files if a ransom payment is made. [Maze](https://attack.mitre.org/software/S0449) has used the ChaCha algorithm, based on Salsa20, and an RSA algorithm to encrypt files.(Citation: FireEye Maze May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--006e029e-0714-4f99-befd-53b9fbc7c8c8`.
