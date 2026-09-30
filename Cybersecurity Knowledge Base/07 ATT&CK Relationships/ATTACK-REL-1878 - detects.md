---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0117"
target_object: "T1036.004"
stix_relationship_id: "relationship--f0f024f2-b4c2-432e-a3b9-5a2e5ecee53f"
---
# Relationship 1878: DET0117 — detects → T1036.004

**Source object:** [[01 ATT&CK/DET0117 - Detection of Masqueraded Tasks or Services with Suspicious Naming and Execution|DET0117: Detection of Masqueraded Tasks or Services with Suspicious Naming and Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0f024f2-b4c2-432e-a3b9-5a2e5ecee53f`.
