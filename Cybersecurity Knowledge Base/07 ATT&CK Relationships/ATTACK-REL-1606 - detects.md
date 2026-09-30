---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0464"
target_object: "T1016.002"
stix_relationship_id: "relationship--4d8df352-7fc2-43a8-93d3-ad7a24f15175"
---
# Relationship 1606: DET0464 — detects → T1016.002

**Source object:** [[01 ATT&CK/DET0464 - Behavioral Detection of Wi-Fi Discovery Activity|DET0464: Behavioral Detection of Wi-Fi Discovery Activity]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1016.002 - Wi-Fi Discovery|T1016.002: Wi-Fi Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4d8df352-7fc2-43a8-93d3-ad7a24f15175`.
