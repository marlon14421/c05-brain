---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0514"
target_object: "T1573.001"
stix_relationship_id: "relationship--90ca7f0e-f0fd-47d5-9d40-8ae6d77c0897"
---
# Relationship 5441: S0514 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0514 - WellMess|S0514: WellMess]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WellMess](https://attack.mitre.org/software/S0514) can encrypt HTTP POST data using RC6 and a dynamically generated AES key encrypted with a hard coded RSA public key.(Citation: PWC WellMess July 2020)(Citation: PWC WellMess C2 August 2020)(Citation: CISA WellMess July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--90ca7f0e-f0fd-47d5-9d40-8ae6d77c0897`.
