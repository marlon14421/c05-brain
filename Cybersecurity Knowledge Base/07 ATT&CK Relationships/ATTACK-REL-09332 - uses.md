---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0352"
target_object: "T1573.001"
stix_relationship_id: "relationship--47b5c142-c0e5-4754-ae7f-b95bf01d3a5b"
---
# Relationship 9332: S0352 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0352 - OSX_OCEANLOTUS.D|S0352: OSX_OCEANLOTUS.D]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSX_OCEANLOTUS.D](https://attack.mitre.org/software/S0352) encrypts data sent back to the C2 using AES in CBC mode with a null initialization vector (IV) and a key sent from the server that is padded to 32 bytes.(Citation: Unit42 OceanLotus 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--47b5c142-c0e5-4754-ae7f-b95bf01d3a5b`.
