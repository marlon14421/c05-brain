---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0597"
target_object: "T1555.005"
stix_relationship_id: "relationship--6a8c842f-73a3-4620-be9c-827895df25f0"
---
# Relationship 1665: DET0597 — detects → T1555.005

**Source object:** [[01 ATT&CK/DET0597 - Detect Unauthorized Access to Password Managers|DET0597: Detect Unauthorized Access to Password Managers]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1555.005 - Password Managers|T1555.005: Password Managers]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a8c842f-73a3-4620-be9c-827895df25f0`.
