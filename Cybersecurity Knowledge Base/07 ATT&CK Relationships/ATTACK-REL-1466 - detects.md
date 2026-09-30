---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0492"
target_object: "T1578.005"
stix_relationship_id: "relationship--834fe398-2ad2-4b19-88cd-cd6da2d5b46c"
---
# Relationship 1466: DET0492 — detects → T1578.005

**Source object:** [[01 ATT&CK/DET0492 - Detection Strategy for Modify Cloud Compute Infrastructure- Modify Cloud Compute Conf|DET0492: Detection Strategy for Modify Cloud Compute Infrastructure: Modify Cloud Compute Configurations]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1578.005 - Modify Cloud Compute Configurations|T1578.005: Modify Cloud Compute Configurations]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--834fe398-2ad2-4b19-88cd-cd6da2d5b46c`.
