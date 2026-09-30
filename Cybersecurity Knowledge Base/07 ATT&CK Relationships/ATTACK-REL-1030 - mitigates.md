---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1218.004"
stix_relationship_id: "relationship--21ce896b-e6b5-4075-8d97-6b59c269247c"
---
# Relationship 1030: M1038 — mitigates → T1218.004

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1218.004 - InstallUtil|T1218.004: InstallUtil]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use application control configured to block execution of InstallUtil.exe if it is not required for a given system or network to prevent potential misuse by adversaries.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--21ce896b-e6b5-4075-8d97-6b59c269247c`.
