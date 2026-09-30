---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0187"
target_object: "T1685.001"
stix_relationship_id: "relationship--4f1b19e0-5471-40c6-8bfa-f15b469d144a"
---
# Relationship 1944: DET0187 — detects → T1685.001

**Source object:** [[01 ATT&CK/DET0187 - Detect Disabled Windows Event Log|DET0187: Detect Disabled Windows Event Log]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1685.001 - Disable or Modify Windows Event Log|T1685.001: Disable or Modify Windows Event Log]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f1b19e0-5471-40c6-8bfa-f15b469d144a`.
