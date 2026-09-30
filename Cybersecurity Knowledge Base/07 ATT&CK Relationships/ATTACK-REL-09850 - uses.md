---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9020"
target_object: "T1573.001"
stix_relationship_id: "relationship--30a4c248-9477-4eba-8925-f559682b0a1f"
---
# Relationship 9850: S9020 — uses → T1573.001

**Source object:** [[01 ATT&CK/S9020 - LODEINFO|S9020: LODEINFO]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LODEINFO](https://attack.mitre.org/software/S9020) can encrypt C2 communication with a hardcoded (NV4HDOeOVyL) Vigenere cipher key.(Citation: Kaspersky LODEINFO Part II OCT 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30a4c248-9477-4eba-8925-f559682b0a1f`.
