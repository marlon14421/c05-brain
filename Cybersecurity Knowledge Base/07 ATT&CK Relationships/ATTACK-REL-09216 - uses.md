---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0001"
target_object: "T1573.001"
stix_relationship_id: "relationship--fa426e9e-7e77-4c1b-b03c-00a4ae45ac6c"
---
# Relationship 9216: C0001 — uses → T1573.001

**Source object:** [[01 ATT&CK/C0001 - Frankenstein|C0001: Frankenstein]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Frankenstein](https://attack.mitre.org/campaigns/C0001), the threat actors communicated with C2 via an encrypted RC4 byte stream and AES-CBC.(Citation: Talos Frankenstein June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa426e9e-7e77-4c1b-b03c-00a4ae45ac6c`.
