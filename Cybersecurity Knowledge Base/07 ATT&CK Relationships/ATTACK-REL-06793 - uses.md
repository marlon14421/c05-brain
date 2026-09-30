---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0033"
target_object: "T1087.001"
stix_relationship_id: "relationship--b93cfd4f-113c-4769-81c9-e710ed0b5f4e"
---
# Relationship 6793: G0033 — uses → T1087.001

**Source object:** [[01 ATT&CK/G0033 - Poseidon Group|G0033: Poseidon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Poseidon Group](https://attack.mitre.org/groups/G0033) searches for administrator accounts on both the local victim machine and the network.(Citation: Kaspersky Poseidon Group)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b93cfd4f-113c-4769-81c9-e710ed0b5f4e`.
