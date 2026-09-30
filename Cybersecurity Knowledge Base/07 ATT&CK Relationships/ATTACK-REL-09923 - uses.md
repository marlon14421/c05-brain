---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0074"
target_object: "T1573.001"
stix_relationship_id: "relationship--4e5dff55-c686-4fa6-bad1-caa8507083d9"
---
# Relationship 9923: S0074 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0074 - Sakula|S0074: Sakula]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sakula](https://attack.mitre.org/software/S0074) encodes C2 traffic with single-byte XOR keys.(Citation: Dell Sakula)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e5dff55-c686-4fa6-bad1-caa8507083d9`.
