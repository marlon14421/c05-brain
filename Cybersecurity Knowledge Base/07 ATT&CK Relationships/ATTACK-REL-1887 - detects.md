---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0424"
target_object: "T1686.001"
stix_relationship_id: "relationship--ed04931d-0b5b-4523-a663-f3286298e389"
---
# Relationship 1887: DET0424 — detects → T1686.001

**Source object:** [[01 ATT&CK/DET0424 - Detection Strategy for Disable or Modify Cloud Firewall|DET0424: Detection Strategy for Disable or Modify Cloud Firewall]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1686.001 - Cloud Firewall|T1686.001: Cloud Firewall]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed04931d-0b5b-4523-a663-f3286298e389`.
