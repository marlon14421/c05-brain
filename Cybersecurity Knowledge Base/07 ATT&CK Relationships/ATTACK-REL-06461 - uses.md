---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0141"
target_object: "T1573.001"
stix_relationship_id: "relationship--1a20c3db-a33c-4129-9fad-3f5605c0cbcb"
---
# Relationship 6461: S0141 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0141 - Winnti for Windows|S0141: Winnti for Windows]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Winnti for Windows](https://attack.mitre.org/software/S0141) can XOR encrypt C2 traffic.(Citation: Novetta Winnti April 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1a20c3db-a33c-4129-9fad-3f5605c0cbcb`.
