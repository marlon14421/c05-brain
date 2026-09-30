---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0062"
target_object: "T1685.004"
stix_relationship_id: "relationship--7a05c6f9-b4c1-4490-8f4a-9033e252dfda"
---
# Relationship 1806: DET0062 — detects → T1685.004

**Source object:** [[01 ATT&CK/DET0062 - Detection Strategy for Disable or Modify Linux Audit System Log|DET0062: Detection Strategy for Disable or Modify Linux Audit System Log]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1685.004 - Disable or Modify Linux Audit System Log|T1685.004: Disable or Modify Linux Audit System Log]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a05c6f9-b4c1-4490-8f4a-9033e252dfda`.
