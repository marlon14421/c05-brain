---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1031"
target_object: "T1573.001"
stix_relationship_id: "relationship--ffe85478-e3ed-4856-b4ae-03a7b693e381"
---
# Relationship 9638: S1031 — uses → T1573.001

**Source object:** [[01 ATT&CK/S1031 - PingPull|S1031: PingPull]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PingPull](https://attack.mitre.org/software/S1031) can use AES, in cipher block chaining (CBC) mode padded with PKCS5, to encrypt C2 server communications.(Citation: Unit 42 PingPull Jun 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ffe85478-e3ed-4856-b4ae-03a7b693e381`.
