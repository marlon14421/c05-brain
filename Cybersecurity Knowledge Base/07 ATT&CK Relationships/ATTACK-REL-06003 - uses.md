---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9018"
target_object: "T1027.013"
stix_relationship_id: "relationship--6bf5bf94-f5d8-48ca-9805-9ffb2ccdd551"
---
# Relationship 6003: S9018 — uses → T1027.013

**Source object:** [[01 ATT&CK/S9018 - HeartCrypt|S9018: HeartCrypt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HeartCrypt](https://attack.mitre.org/software/S9018) strings are encrypted via a single-byte XOR operation rotating over a hard-coded key, possibly provided by the PaaS customers. (Citation: Palo Alto HeartCrypt DEC 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6bf5bf94-f5d8-48ca-9805-9ffb2ccdd551`.
