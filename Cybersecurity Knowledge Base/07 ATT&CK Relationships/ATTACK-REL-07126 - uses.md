---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0068"
target_object: "T1573.001"
stix_relationship_id: "relationship--5b3d2b2f-73f4-4fef-9cb9-b11db3eb4c4f"
---
# Relationship 7126: S0068 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0068 - httpclient|S0068: httpclient]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[httpclient](https://attack.mitre.org/software/S0068) encrypts C2 content with XOR using a single byte, 0x12.(Citation: CrowdStrike Putter Panda)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b3d2b2f-73f4-4fef-9cb9-b11db3eb4c4f`.
