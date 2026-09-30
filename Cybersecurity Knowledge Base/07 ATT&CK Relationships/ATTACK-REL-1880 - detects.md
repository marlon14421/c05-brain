---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0393"
target_object: "T1548.005"
stix_relationship_id: "relationship--0a7998f6-19aa-40f6-af2b-ca799786c601"
---
# Relationship 1880: DET0393 — detects → T1548.005

**Source object:** [[01 ATT&CK/DET0393 - Detection Strategy for Temporary Elevated Cloud Access Abuse (T1548.005)|DET0393: Detection Strategy for Temporary Elevated Cloud Access Abuse (T1548.005)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1548.005 - Temporary Elevated Cloud Access|T1548.005: Temporary Elevated Cloud Access]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0a7998f6-19aa-40f6-af2b-ca799786c601`.
