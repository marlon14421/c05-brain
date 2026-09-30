---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0046"
target_object: "T1497"
stix_relationship_id: "relationship--3a1c35eb-615c-4c4a-98ee-ca2b9d25fb01"
---
# Relationship 1486: DET0046 — detects → T1497

**Source object:** [[01 ATT&CK/DET0046 - Detection Strategy for T1497 Virtualization-Sandbox Evasion|DET0046: Detection Strategy for T1497 Virtualization/Sandbox Evasion]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1497 - Virtualization-Sandbox Evasion|T1497: Virtualization/Sandbox Evasion]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a1c35eb-615c-4c4a-98ee-ca2b9d25fb01`.
