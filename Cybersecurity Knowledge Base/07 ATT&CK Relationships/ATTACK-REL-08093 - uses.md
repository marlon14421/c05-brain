---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0627"
target_object: "T1573.001"
stix_relationship_id: "relationship--b947983f-2c0a-4082-b102-8f8497e2b045"
---
# Relationship 8093: S0627 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0627 - SodaMaster|S0627: SodaMaster]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SodaMaster](https://attack.mitre.org/software/S0627) can use RC4 to encrypt C2 communications.(Citation: Securelist APT10 March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b947983f-2c0a-4082-b102-8f8497e2b045`.
