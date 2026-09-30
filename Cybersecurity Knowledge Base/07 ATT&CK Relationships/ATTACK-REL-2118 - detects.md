---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0410"
target_object: "T1039"
stix_relationship_id: "relationship--7141f45b-597e-48a6-9b27-f3f2730dad87"
---
# Relationship 2118: DET0410 — detects → T1039

**Source object:** [[01 ATT&CK/DET0410 - Detection Strategy for Data from Network Shared Drive|DET0410: Detection Strategy for Data from Network Shared Drive]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1039 - Data from Network Shared Drive|T1039: Data from Network Shared Drive]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7141f45b-597e-48a6-9b27-f3f2730dad87`.
