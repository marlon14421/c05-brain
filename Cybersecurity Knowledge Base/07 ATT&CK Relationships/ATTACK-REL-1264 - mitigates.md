---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1216.001"
stix_relationship_id: "relationship--387cdc83-fc81-499e-8875-e3d4789af9c3"
---
# Relationship 1264: M1038 — mitigates → T1216.001

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1216.001 - PubPrn|T1216.001: PubPrn]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Certain signed scripts that can be used to execute other programs may not be necessary within a given environment. Use application control configured to block execution of these scripts if they are not required for a given system or network to prevent potential misuse by adversaries.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--387cdc83-fc81-499e-8875-e3d4789af9c3`.
