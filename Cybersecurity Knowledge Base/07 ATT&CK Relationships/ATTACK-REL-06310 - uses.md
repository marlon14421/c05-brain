---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0200"
target_object: "T1573.001"
stix_relationship_id: "relationship--36b2817e-5f07-4f70-927c-8e04b955d5a3"
---
# Relationship 6310: S0200 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0200 - Dipsind|S0200: Dipsind]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dipsind](https://attack.mitre.org/software/S0200) encrypts C2 data with AES256 in ECB mode.(Citation: Microsoft PLATINUM April 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36b2817e-5f07-4f70-927c-8e04b955d5a3`.
